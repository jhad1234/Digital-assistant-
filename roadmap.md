خريطة الطريق للمشروع (Roadmap)

MVP (4-8 أسابيع):
- إعداد المستودع وبنية المشروع الأساسية.
- API Gateway + مصادقة (بسيطة) + تطبيق Flutter للدردشة (نموذج أولي).
- AI Core: NLU + مخطط مهمات بسيط + LLM Adapter لمزوّد واحد.
- وكلاء أساسيون: ContentAgent + Executor.
- ذاكرة قصيرة وبسيط PostgreSQL و audit logs.

v1 (3 أشهر):
- نظام Multi-Agent Manager و Message Bus.
- إضافة Vector DB للبحث الدلالي.
- Plugin system أساسي.
- Integrations: Google Drive, Notion, GitHub.
- Basic policy engine و confirmation flows.

v2 (بعد 6-12 شهر):
- Advanced Planner و workflow composer واجهة سحب وإفلات.
- Marketplace للإضافات و sandboxed plugins.
- دعم on-premise LLMs و تحكم تكلفة متقدم.
- تحسين المراقبة، الآليات الذاتية للتطوير، وتوسيع قدرات الوكلاء.

ملاحظات تنفيذية:
- ابدأ بوحدة واحدة عاملة (ContentAgent) ثم أضف الاتصالات.
- اجعل كل مكوّن قابل للاختبار مستقلًا (microservice + tests).
- ضع أولاً حدود أمان و auditing قبل ضبط عمليات نشر تلقائية.
