[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/2AJIyfdd)
## Dataset

Деректер жинағы автомобиль компаниясының сату деректерін қамтиды. Датасетте 778 жол және 20 баған бар. 

Баған атауы	Сипаттама

ORDERNUMBER	Бұл баған әрбір тапсырысқа тағайындалған бірегей сәйкестендіру нөмірін білдіреді.

QUANTITYORDERED	Ол әрбір тапсырыста тапсырыс берілген заттардың санын көрсетеді.

PRICEEACH	Бұл баған тапсырыстағы әрбір элементтің бағасын көрсетеді.

ORDERLINENUMBER	Ол тапсырыстағы әрбір элементтің жол нөмірін көрсетеді.

SALES	Бұл баған әрбір тауардың бағасына тапсырыс санын көбейту арқылы есептелетін әрбір тапсырыс үшін жалпы сату сомасын 
білдіреді.

ORDERDATE	Ол тапсырыс берілген күнді білдіреді.

DAYS_SINCE_LASTORDER	Бұл баған әрбір тұтынушы үшін соңғы тапсырыстан бері өткен күндер санын көрсетеді. Оны 
тұтынушылардың сатып алу үлгілерін талдау үшін пайдалануға болады.

STATUS	Ол тапсырыс күйін көрсетеді, мысалы, «Жіберілді», «Өзделуде», «Бас тартылды», «Даулы», «Күтуде» немесе «Шешілді».

PRODUCTLINE	Бұл баған әрбір элемент жататын өнім желісі санаттарын көрсетеді.

MSRP	Ол Өндірушінің ұсынған бөлшек сауда бағасын білдіреді және әрбір тауар үшін ұсынылған сату бағасын білдіреді.

PRODUCTCODE	Бұл баған әрбір өнімге тағайындалған бірегей кодты білдіреді.

CUSTOMERNAME	Ол тапсырыс берген тапсырыс берушінің атын білдіреді.

PHONE	Бұл баған тұтынушының байланыс телефон нөмірін қамтиды.

ADDRESSLINE1	Ол тұтынушы мекенжайының бірінші жолын білдіреді.

CITY	Бұл баған тұтынушы орналасқан қаланы көрсетеді.

POSTALCODE	Ол тұтынушының мекенжайымен байланысты пошта индексін немесе пошта индексін білдіреді.

COUNTRY	Бұл баған тұтынушы орналасқан елді көрсетеді.

CONTACTLASTNAME	Ол тұтынушымен байланысқан тұлғаның тегін білдіреді.

CONTACTFIRSTNAME	Бұл баған тұтынушымен байланыстырылған байланыс тұлғасының атын білдіреді.

DEALSIZE	Ол «Кіші», «Орташа» немесе «Үлкен» санаттары болып табылатын мәміле немесе тапсырыс өлшемін көрсетеді.

`
## Plan

Кіріспе (Introduction):

Мәліметтердің жалпы сипаттамасы (қандай дереккөзден алынғаны, қандай мақсатта пайдаланылатыны).

Мәліметтердің негізгі ерекшеліктері (қандай бағандар бар, қанша жазба бар, қандай деректер талданады).

2. Деректерді тазалау (Data Cleaning):

Жоғалған мәндерді тексеру және өңдеу.

Сандық бағандардың деректер типін тексеру (егер қажет болса, өзгерту).

Қате немесе қайталанған жазбаларды жою.

Аномалияларды анықтау және өңдеу (мысалы, шектен тыс үлкен немесе кіші мәндер).

3. Деректерді зерттеу (Exploratory Data Analysis, EDA):

Сандық деректер:

Орташа мән, медиана, стандартты ауытқу сияқты сипаттамалық статистикаларды есептеу.

Баға мен тапсырыс санының үлестірілімін зерттеу.

Категориялық деректер:

Тапсырыс күйі, өнім санаттары, т.б. бойынша жиіліктерді анықтау.

Графиктер:

Гистограмма (баға, тапсырыс саны).

Бағандық диаграммалар (тапсырыс күйі, өнім санаттары).

Корреляциялық матрица (сандық деректер арасындағы байланыс).

4. Деректерді түрлендіру (Data Transformation):

Жаңа бағандар қосу:

Жалпы тапсырыс сомасы (QUANTITYORDERED × PRICEEACH).

Ірі тапсырыстарды (LARGE_ORDER) анықтайтын баған қосу.

Категориялық деректерді сандыққа ауыстыру (мысалы, STATUS бағанын кодтау).

5. Қорытындылар (Conclusions):

Зерттеу барысында алынған негізгі нәтижелер мен тұжырымдар.
