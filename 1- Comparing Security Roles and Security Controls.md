# Comparing Security Roles and Security Controls

## Information Security

**info sec** ⇒  او بيانات الموظفين passwords ودا بيكون القسم المختص انو يحمي الداتا بتاعت الشركه سواء 

عشان احقق ال Information Security لازم اطبق تلت حاجات وهما (CIA) : 

- **Confidentiality** : ودا معناه السريه او الخصوصيه ودا بحدد فيها مين الاشخاص اللي يقدرو يوصلو للداتا بتاعت الشركه عشان مينفعش اسيبها سداح مداح كدا
- **Integrity** : ودا سلامة البيانات بمعني ايه ؟ بمعني اني مش اي حد ليه صلاحيه انو يوصل للداتا انو يقدر يعدل عليها او يمسحها لا في ناس معينه بس هما اللي يقدرو يعملو كدا
- **Availability** : ودي التوافريه ودي فيها بتأكد البيانات تمام وسليمه ومفيهاش اي خلل ومتكونش مسروقه برضو
- **Non-repudiation** : ودا حاجه مش ضروريه اوي بس بتزود الامن بتاع الشركه اللي هو مبدأ عدم الانكار طب ايه ده؟ دا المفروض لو حد عمل حاجه مخالفه زي انو مسح حاجه من الداتا او عدل عليها او عمل اختراق من -فا ساعتها انا هعرف مين عمل ايه فا مش هيقدر ينكرlog جوا الشركه يعني بقدر اجيبو عادي من حاجه

***فا لو قدرت اطبق التلت مفاهيم دول عالاقل هيكون السيستم بتاعي محمي وصعب انو يكون معرض للاختراق***

---

## INFORMATION SECURITY ROLES AND RESPONSIBILITIES

**Security Policy** : 

ودي وثيقه الامن , يعني لما تتعين ف شركه معينه كا Security بيدوك حاجه اسمها وثيقه الامن دي بتكون فيها كل شئ عن الامن في المؤسسه بالكامل ودي بيعرفوك فيها كل المعلومات الخاصه بالشركه سواء من باسوردات او اجهزه او الاقسام والموظفين اللي فيهم

## INFORMATION SECURITY BUSINESS UNITS

**1- Security Operations Center (SOC) :**

ودا بيكون تيم او قسم مختص بمراقبه كل ال traffics اللي ماشيه فالشبكه عشان يراقبو كل حاجه ولو في هجمه بتحصل مثلا طب لو في attack حصل هيعملو ايه ؟ بص لو attack ضعيف هيتعاملو هما انما لو كبير بيكون في تيم تاني بقي مختص للحاجات دي اسمه Incident Response

**2- Incident Response :** 

ودا بيكون التيم المختص للتعامل مع ال attacks اللي بتحصل وبيحاول انو يصدها

---

## SECURITY CONTROL CATEGORIES

ودا هنوضح فيها طريقه التحكم في انظمة الامن في المؤسسه بتاعتي , يلا بينا

**1- Technical :**

ودا نوع تأمين من خلال اني اشتري اجهزه تحميني زي ال IDS او Firewalls

**2- Operational :** 

ودا نوع تأمين بشري اني اجيب حارس مثلا يأمنلي ال Data Center بتاعتي 

**3- Managerial :** 

ودا قسم الادرايين والمشرفين اللي هما بيدو الموافقه علي شراء الاجهزه والمعدات دي كلها 

**4- Physical :** 

ودا نوع تأمين باين من اسمه حاجه بتتلمس زي اني اجيب كاميرات مراقبه او اجهزه انذار مثلا

**5- Deterrent :** 

ودا نوع تأمين بيكون تنيهي للسارق او للهاكر زي لافتات تنبيهيه بتحذرو زي “المكان مراقب بالكاميرات”

**6- Compensating :** 

ودا الجزء التعويضي ودا نوع تأمين بحيث لو في حاجه حصل فيها عطل يكون عندي البديل علاطول ومجهزه ف اي وقت

---

## SECURITY CONTROL FUNCTIONAL TYPES

ياتري بعد ما شرحنا دا كلو ليه , ايه الاهداف من اني اعمل Security Control كويس او الحاجه اللي هوصلها , تعالي اقولك

**1- Preventive :** 

المنع , ودا اني اكشف الهجوم واوفقه قبل ما يحصل اصلا زي جهاز ال IPS مثلا

**2- Detective :** 

الكشف , ودا لما بتحصل attack  بيكون عندي اجهزه او اشخاص بيكتشفو الهجمه دي بس هيا بتكون حصلت بالفعل زي جهاز ال IDS مثلا 

**3- Corrective :** 

التصليح والتصحيح بحيث لما تحصل الattack والداتا عندي باظت مثلا يكون عندي backup ليها تاني عشان اقدر ارجعها

---