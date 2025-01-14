# Summarizing Risk Management Concepts

*معظم كلام انهارده هو اداري شويه ليه علاقه بالاداريين مش تكينيكال زي ما كنا متعودين في الكورس*

## RISK MANAGEMENT PROCESSES

- **Risk management**

-عملية ادارة المخاطر وفيها بقيم واحدد نقاط الضعف وتأثيرها وايه الخسائر المتوقعه

### الخمس مراحل في عملية ال Risk Management

1. **Identify mission essential functions**
- دي برتب فيها اولوياتي يعني بشوف انهي اجهزة ليها اولوليه عن التانيه وابدأ اتعامل معاها واحللها والكلام ده كلو يعني مثلا اركز جهدي علي قسم واجهزة ال IT الاول ولا قسم ال HR مثلا لأ طبعا اركز علي ال IT وبعد كدا ال HR
1. **Identify vulnerabilities**
- بمسك بقي كل جهاز واطلع منو نقاط الضعف اللي ممكن تتسبب في حدوث Risk
1. **Identify threats**
- بحدد بقي هنا التهديدات اللي ممكن تحصلي
- في حد هيجي يسأل يقول هو ايه الفرق بين ال Vulnerabilities وال Threat هقولك ياغبي منتا لو تفتكر ف اول الكورس خالص ف اول درس كنا بنقول اني لو في ثغره حصلها استغلال هتسببلي Threat

*Vulnerabilities + Exploit = Threat*

1. **Analyze business impacts**
- هنا بشوف التأثيرات اللي حصلت علي البيزنس بتاعي يعني العملاء ايه انطباعهم طب خسرنا كام
1. **Identify risk response**
- بواجه ال Risk هيا شبيه شويه لل Incident Response وبعد ال risk بحط ضوابط امنيه عشان امنع تكرارها تاني

---

## RISK TYPES

- **External**

-ممكن التهديد يجيلي خارجي ودا الاكثر انتشارا عامة

-ممكن ظاهره طبيعيه تمثلي Risk طب ازاي؟ يعني مثلا دلوقتي كورونا لما انتشرت المدير قالكو لأ اشتغلو من البيت فا ممكن الشركه مكنتش منظمه السيرفرات انها تستقبل طلبات من البيت او من مكان خارج الشركه عموما فا ممكن ال Attacker يستغل حاجه زي دي مثلا

- **Internal**

-ممكن الهجمه تيجي من الداخل سواء من اجهزه او موظفين

-او ممكن يجي من طرف ليه Temporary Access يعني مثلا السيرفرات محدش عندي ف الشركه بيعرف يتعامل معاها فا انا اتعاقدت مع شركة معينه متخصصه ف كدا عشان تيجي تسطبلي السيرفرات وتمشي تاني فا ممكن ال Risk ييجي منهم

- **Multiparty**

-هنا تأثير ال Risk ممكن يضر اكتر من شركه بس ازاي ده بيحصل؟

-مثلا دلوقتي ف شركتي كل الاجهزه شغاله بنظام الويندوز وشركه تانيه نفس الكلام وشركات كتير بتعتمد علي نظام الويندوز فا اللي عامل نظام الويندوز شركة ميكروسوفت طب افرض ميكروسوفت حصلها attack فا بالتالي كل الشركات اللي بتشتغل بنظام ويندوز هتضرر

- **Intellectual Property (IP) Theft**

-ودي المقصود بيها سرقة بيانات ذات قيمه تجاريه مملوكه

-يعني مثلا اتسرق مني براءة اختراع او حقوق الملكيه الفكريه فا لما حاجات زي دي تتسرق فا انا هخسر لأني بقي في حد غيري بيعمل نفس الحاجه اللي انا كنت منفرد بيها لوحدي

- **Software Compliance/Licensing**

-المقصود بيها سرقة ال License بتاعت برنامج معين زي ما يكون برنامج بفلوس وانت مكركه

- **Legacy Systems**

-الاجهزة القديمه اللي اتشال من عليها الدعم زي ويندوز 7 مثلا لو حد لسه بيستعمل ويندوز 7 فا هو بيعرض نفسه للخطر

---

## QUANTITATIVE and QUALITATIVE RISK ASSESSMENT

### **Quantitative**

- هنا المصطلح ده بيعبر عن كمية الخساره اللي خسرتها من فلوس وعشان احسب الخساره لازم اعرف تلت حاجات:
1. **Single Loss Expectancy (SLE)**
- دا معناها الخساره المتوقعه للجهاز الواحد
1. **Annualized Rate of Occurrence (ARO)**
- عدد مرات الحدوث ف السنه
1. **Annualized Loss Expectancy (ALE)**
- الخساره الكليه اللي خسرتها واللي بعرفها من ضرب SLE * ARO

![image.png](image.png)

### Qualitative

- هنا انا بشوف بقي خسرت ايه بس مش من ناحية الفلوس ولكن من الناحيه المعنويه يعني سمعة الشركه او رضا العملاء بتوعي وهكذا

---

## RISK AVOIDANCE

- وهي الابتعاد عن المخاطر او ابتعد عن النشاط اللي نتايجه هتأدي لمخاطر ف الاخر
- مثال : انا دلوقتي بطور ابلكيشن معين بتاع مخازن مثلا وبعدين بيعتو واكتشفت بعد كدا اني فيه نقاط ضعف هنا هتجنب الموضوع ده وهمسح الابلكيشن كله

---

## RISK TRANSFERENCE AND RISK ACCEPTANCE

- **Transference (or sharing)**

-هنا بعين المخاطر دي او المسؤول عنها وحلها هيا جهه خارجيه زي مثلا شركات التأمين لو عملت حادثه هما اللي هيتولو تصليح العربيه بتاعتي وهيتحملو معايا جزء من تكلفة التصليح

- **Risk Acceptance**

-قبول المخاطر دي عكس ال Avoidance شويه ليه؟ لأني هنا لو في risk معين ف حاجه معينه ف الابلكيشن بكرفلها ومبديهاش اي اهتمام لأني مثلا الحاجه دي محدش بيستخدمها كتير

---

## BUSINESS IMPACT ANALYSIS

- التأثير الفعلي علي البيزنس بتاعتي لما يحصل Risk يعني بحلل انا خسرت قد ايه طب انا السيستم بتاعي فضل واقع لحد امتي طب ايه الوقت المحتمل اللي هاخده عشان اقدر ارجع السيستم بتاعي

---

## MISSION ESSENTIAL FUNCTIONS

- **Maximum tolerable downtime (MTD)**

-هي اطول فتره زمنيه هيستغرقها السيستم بتاعي لما يحصل انقطاع في وظيفة العمل

-مثال: دلوقتي مثلا عندي شركة معدات طبيه حصل كارثه طبيعيه والتصنيع وقف فا هيشوفو المخزن هيلاقو في معدات طبيه بس هتكفيهم لمدة تلت شهور بعد التلت شهور الشركة هتقف هنا ال MTD هو 3 شهور

- **Recovery time objective (RTO)**

-دا الوقت المستغرق عشان اعرف المشكله واعالجها عشان اقدر ارجع اشتغل تاني

- **Work Recovery Time (WRT)**

-هنا انا خلاص الشغل رجع بس بياخد وقت علي ما اظبط الدنيا بقي وارجع اشتغل تاني يعني مثلا لو هنتكلم علي مثال المعدات الطبيه علي ما اجيب المعدات وارصها ف المخزن وابدأ اشتغل بيهم دا WRT

---

## SINGLE POINTS OF FAILURE

- ال SPoF هو الاعتماد علي جهاز واحد ف البيزنس بتاعي يعني مثلا افرض اني عندي switch واحد بس فا لو حصل attack مثلا علي الشبكه فا ال switch هيتعطل طب لو كان عندي واحد تاني غيره لا ساعتها مش هيتعطل
- فا حل المشكله دي هو ال redundant او التكرار واجيب اكتر من جهاز بيعمل نفس الوظيفه فا كدا انا ضمنت ان لو حصل عطل في جهاز معين هيكون في بديل ليه يشتغل مكانه وبكدا مفيش خوف من ال Single Point of Failure

**Mean Time To Failure (MTTF)**

- المقصود هنا ال MTTF هو الوقت المتوقع لحدوث عطل في الأجهزة غير القابلة للإصلاح - يعني الأجهزة اللي لازم تتغير على طول لما تتعطل

![image.png](image%201.png)

**Mean time to repair (MTTR)**

-الوقت المستغرق في إصلاح أو استبدال المكونات المعطلة

---

## DISASTERS

- مصطلح الكارثه بنقوله علي اي حاجه بتهدد الوظائف الاساسيه فالبيزنس بتاعي
- الزلازل مثلا ممكن تدمر ال data center بتاعتي
- يعني ممكن نقسم الكوارث لتلت حاجات وهما:
1. External or Internal
2. Person-Made
3. Environmental
- **Disaster recovery plans (DRPs)**

-الخطط اللي انا بحطها عشان اواجه الكارثة دي وأقلل من الأضرار بتاعتها

---