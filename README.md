# midterm-visualization-with-modern-data-science

Midterm: Visualization with Modern Data Science 2025.

## 01. Write a SQL statement that is able to show the number of rows for certain tables given `taiwan_election_2024.db`.

```
table_name	number_of_rows
candidates	331
districts	17795
parties	35
```

## 02. Write a SQL statement that is able to show the number of columns for certain tables given `taiwan_election_2024.db`.

```
table_name	number_of_columns
candidates	4
districts	5
parties	2
```

## 03. Based on the previous query results, write a SQL statement that is able to show both the number of rows and columns for certain tables given `taiwan_election_2024.db`.

```
table_name	number_of_rows	number_of_columns
candidates	331	4
districts	17795	5
parties	35	2
```

## 04. Write a SQL statement that is able to show earliest and latest votes tallied time given `taiwan_election_2024.db`.

```
label	vote_tallied_at
earliest	2024-01-13 16:30:49
latest	2024-01-13 21:56:59
```

## 05. Based on the previous query result, write a SQL statement that is able to find the corresponding polling places.

```
county	town	polling_place	vote_tallied_at
宜蘭縣	大同鄉	421	2024-01-13 16:30:49
新竹縣	竹北市	25	2024-01-13 21:56:59
```

## 06. Write a SQL statement that is able to show earliest 5 and latest 5 votes tallied time given `taiwan_election_2024.db`.

```
label	vote_tallied_at
earliest	2024-01-13 16:30:49
earliest	2024-01-13 16:39:59
earliest	2024-01-13 16:40:11
earliest	2024-01-13 16:41:58
earliest	2024-01-13 16:43:04
latest	2024-01-13 21:36:21
latest	2024-01-13 21:40:31
latest	2024-01-13 21:45:08
latest	2024-01-13 21:54:41
latest	2024-01-13 21:56:59
```

## 07. Based on the previous query result, write a SQL statement that is able to find the corresponding polling places.

```
county	town	polling_place	vote_tallied_at
宜蘭縣	大同鄉	421	2024-01-13 16:30:49
澎湖縣	湖西鄉	63	2024-01-13 16:39:59
澎湖縣	西嶼鄉	98	2024-01-13 16:40:11
嘉義縣	布袋鎮	159	2024-01-13 16:41:58
澎湖縣	馬公市	53	2024-01-13 16:43:04
基隆市	信義區	76	2024-01-13 21:36:21
臺北市	松山區	654	2024-01-13 21:40:31
基隆市	七堵區	284	2024-01-13 21:45:08
彰化縣	和美鎮	91	2024-01-13 21:54:41
新竹縣	竹北市	25	2024-01-13 21:56:59
```

## 08. Write a SQL statement that is able to show the most votes received and the least votes received by a regional legislator candidate.

```
label	min_max_votes
maximun	158596
minimum	136
```

## 09. Based on the previous query result, write a SQL statement that is able to show the information about the candidates.

```
legislator_region	party	name	sum_votes
新北市第1選舉區	中國國民黨	洪孟楷	158596
臺北市第8選舉區	興中同盟會	胡之壯	136
```

## 10. Write a SQL statement that is able to show the summarized regional legislator results given `taiwan_election_2024.db`.

```
legislator_region	party	name	sum_votes
南投縣第1選舉區	中國國民黨	馬文君	68890
南投縣第1選舉區	勞動黨	許文忠	3577
南投縣第1選舉區	小民參政歐巴桑聯盟	李圓恩	3035
南投縣第1選舉區	民主進步黨	蔡銘軒	50886
南投縣第1選舉區	無	林金潭	3373
南投縣第2選舉區	中國國民黨	游顥	70012
南投縣第2選舉區	民主進步黨	蔡培慧	66551
南投縣第2選舉區	無	陳癸佑	4023
嘉義市選舉區	中國國民黨	張秀華	66822
嘉義市選舉區	小民參政歐巴桑聯盟	陳玥妗	6232
嘉義市選舉區	復康聯盟黨	蔡松益	839
嘉義市選舉區	民主進步黨	王美惠	78069
嘉義市選舉區	無	簡明廉	1219
嘉義市選舉區	臺灣雙語無法黨	林智勲	990
嘉義縣第1選舉區	中國國民黨	詹琬蓁	54097
嘉義縣第1選舉區	民主進步黨	蔡易餘	78551
嘉義縣第2選舉區	制度救世島	簡銘傑	2499
嘉義縣第2選舉區	台灣維新	黃一哲	1213
嘉義縣第2選舉區	民主進步黨	陳冠廷	73598
嘉義縣第2選舉區	無	廖昱婧	6601
嘉義縣第2選舉區	無	林國慶	64778
基隆市選舉區	中國國民黨	林沛祥	91986
基隆市選舉區	家庭基本收入	邱紹祐	2361
基隆市選舉區	小民參政歐巴桑聯盟	謝海菁	8192
基隆市選舉區	民主進步黨	鄭文婷	69741
基隆市選舉區	無	王醒之	37260
基隆市選舉區	無	黃傑陽	1331
宜蘭縣選舉區	中國國民黨	黃琤婷	86120
宜蘭縣選舉區	制度救世島	邱介勲	647
宜蘭縣選舉區	台灣基進	林意評	6201
宜蘭縣選舉區	台灣民眾黨	陳琬惠	53499
宜蘭縣選舉區	民主進步黨	陳俊宇	107308
宜蘭縣選舉區	無	林錦坤	1754
屏東縣第1選舉區	中國國民黨	黃明賢	88518
屏東縣第1選舉區	中華統一促進黨	李孟翰	464
屏東縣第1選舉區	台灣維新	張庭源	496
屏東縣第1選舉區	民主進步黨	鍾佳濱	108723
屏東縣第1選舉區	無	曾鈺庭	1158
屏東縣第1選舉區	無	蔣月惠	25270
屏東縣第2選舉區	中華聯合黨	吳媚宮	4139
屏東縣第2選舉區	人民最大黨	何秋葺	8845
屏東縣第2選舉區	民主進步黨	徐富癸	108923
屏東縣第2選舉區	無	蘇孟淳	82147
彰化縣第1選舉區	中國國民黨	阮厚爵	76448
彰化縣第1選舉區	民主進步黨	陳秀寳	98437
彰化縣第1選舉區	無	蘇群傑	5503
彰化縣第2選舉區	中國國民黨	楊曜聰	81403
彰化縣第2選舉區	民主進步黨	黃秀芳	90688
彰化縣第3選舉區	中國國民黨	謝衣鳯	97681
彰化縣第3選舉區	中華統一促進黨	桂麗娜	683
彰化縣第3選舉區	民主進步黨	吳音寧	78473
彰化縣第3選舉區	無	洪建興	4908
彰化縣第4選舉區	中國國民黨	鄭俊雄	83214
彰化縣第4選舉區	中華文化共和黨	蔡念諶	2583
彰化縣第4選舉區	民主進步黨	陳素月	97608
彰化縣第4選舉區	臺灣雙語無法黨	鄭錫懋	4257
新北市第10選舉區	中國國民黨	林金結	95147
新北市第10選舉區	人民最大黨	孟藹倫	3319
新北市第10選舉區	復康聯盟黨	袁興	2608
新北市第10選舉區	民主進步黨	吳琪銘	103437
新北市第11選舉區	中國國民黨	羅明才	123399
新北市第11選舉區	中華婦女黨	陳聖	1029
新北市第11選舉區	人民最大黨	張家榛	4038
新北市第11選舉區	制度救世島	魏趨安	915
新北市第11選舉區	民主進步黨	曾柏瑜	76237
新北市第11選舉區	無	鄭添泉	2208
新北市第12選舉區	中國國民黨	廖先翔	92489
新北市第12選舉區	台灣維新	陳長志	980
新北市第12選舉區	民主進步黨	賴品妤	81937
新北市第12選舉區	無	楊木火	1023
新北市第12選舉區	無	黃瑞傳	2348
新北市第12選舉區	臺灣雙語無法黨	李佳蒨	3170
新北市第1選舉區	中國國民黨	洪孟楷	158596
新北市第1選舉區	中華統一促進黨	翁藤原	570
新北市第1選舉區	制度救世島	游清池	1867
新北市第1選舉區	台灣維新	徐百弟	2633
新北市第1選舉區	民主進步黨	何博文	106454
新北市第2選舉區	中華統一促進黨	何淯笙	4845
新北市第2選舉區	台灣民眾黨	李有宜	84393
新北市第2選舉區	民主進步黨	林淑芬	118544
新北市第3選舉區	中國國民黨	蔡明堂	79828
新北市第3選舉區	民主進步黨	李坤城	100141
新北市第3選舉區	無	蘇卿彥	4805
新北市第3選舉區	無	陳東雲	3094
新北市第4選舉區	中國國民黨	蔣欣璋	89121
新北市第4選舉區	制度救世島	邱吉均	1002
新北市第4選舉區	民主進步黨	吳秉叡	107772
新北市第4選舉區	無	洪懿馥	14840
新北市第4選舉區	無	蘇輝湟	1924
新北市第5選舉區	中國國民黨	洪佳君	83424
新北市第5選舉區	民主進步黨	蘇巧慧	98586
新北市第6選舉區	中國國民黨	林國春	74652
新北市第6選舉區	司法改革黨	黃淑珍	7450
新北市第6選舉區	民主進步黨	張宏陸	78847
新北市第7選舉區	中國國民黨	葉元之	78134
新北市第7選舉區	小民參政歐巴桑聯盟	劉書婷	15479
新北市第7選舉區	民主進步黨	羅致政	75841
新北市第8選舉區	中國國民黨	張智倫	89808
新北市第8選舉區	台灣民眾黨	邱臣遠	42759
新北市第8選舉區	民主進步黨	吳崢	77763
新北市第9選舉區	中國國民黨	林德福	98260
新北市第9選舉區	台灣維新	陳愷寧	21345
新北市第9選舉區	民主進步黨	莊銘淵	50613
新竹市選舉區	中國國民黨	鄭正鈐	92014
新竹市選舉區	制度救世島	趙福龍	249
新竹市選舉區	司法改革黨	楊清華	566
新竹市選舉區	時代力量	邱顯智	33023
新竹市選舉區	民主進步黨	林志潔	83298
新竹市選舉區	無	柯美蘭	51663
新竹市選舉區	無	王榮德	405
新竹縣第1選舉區	中國國民黨	徐欣瑩	84959
新竹縣第1選舉區	台灣綠黨	余筱菁	15557
新竹縣第1選舉區	台灣維新	劉復嵐	1392
新竹縣第1選舉區	小民參政歐巴桑聯盟	劉台穠	4610
新竹縣第1選舉區	民主進步黨	詹紀緹	45445
新竹縣第2選舉區	中國國民黨	林思銘	76608
新竹縣第2選舉區	時代力量	王婉諭	63566
新竹縣第2選舉區	民主進步黨	曾聖凱	30738
桃園市第1選舉區	中國國民黨	牛煦庭	116571
桃園市第1選舉區	民主進步黨	鄭運鵬	103466
桃園市第1選舉區	無	馬治薇	20600
桃園市第2選舉區	中國國民黨	涂權吉	103697
桃園市第2選舉區	中華統一促進黨	陳志豪	1912
桃園市第2選舉區	民主進步黨	黃世杰	102468
桃園市第2選舉區	無	王思玟	7127
桃園市第3選舉區	中國國民黨	魯明哲	102056
桃園市第3選舉區	制度救世島	戴浙	721
桃園市第3選舉區	小民參政歐巴桑聯盟	徐鶯慈	11258
桃園市第3選舉區	新黨	游智彬	8280
桃園市第3選舉區	民主進步黨	彭俊豪	95581
桃園市第4選舉區	中國國民黨	萬美玲	119430
桃園市第4選舉區	台灣國民黨	甘乃迪	3293
桃園市第4選舉區	民主進步黨	范綱祥	83183
桃園市第4選舉區	無	黃明莉	9426
桃園市第5選舉區	中國國民黨	呂玉玲	89372
桃園市第5選舉區	台灣民眾黨	賴香伶	43691
桃園市第5選舉區	司法改革黨	易乃文	1580
桃園市第5選舉區	民主進步黨	劉仁照	69022
桃園市第6選舉區	中國國民黨	邱若華	81513
桃園市第6選舉區	人民最大黨	翁紹庭	890
桃園市第6選舉區	台灣民眾黨	李慕妍	35183
桃園市第6選舉區	復康聯盟黨	劉睿宸	2689
桃園市第6選舉區	無	葉堂宇	2523
桃園市第6選舉區	無	趙正宇	76346
澎湖縣選舉區	中國國民黨	吳政杰	20226
澎湖縣選舉區	民主進步黨	楊曜	24669
澎湖縣選舉區	無	陳慧娟	3525
臺中市第1選舉區	台灣民眾黨	蔡壁如	72634
臺中市第1選舉區	民主進步黨	蔡其昌	79884
臺中市第1選舉區	無	劉燈鐘	4685
臺中市第1選舉區	無	賴信全	3742
臺中市第2選舉區	中國國民黨	顏寬恒	118962
臺中市第2選舉區	司法正義黨	洪麗華	6331
臺中市第2選舉區	民主進步黨	林靜儀	96151
臺中市第2選舉區	無	紀銘修	2232
臺中市第3選舉區	中國國民黨	楊瓊瓔	106306
臺中市第3選舉區	司法改革黨	張烱春	4368
臺中市第3選舉區	民主進步黨	謝子涵	80128
臺中市第4選舉區	中國國民黨	廖偉翔	119740
臺中市第4選舉區	民主進步黨	張廖萬堅	113350
臺中市第4選舉區	無	陳志彬	3824
臺中市第4選舉區	臺灣雙語無法黨	李海碩	792
臺中市第4選舉區	臺灣雙語無法黨	林中翊	1661
臺中市第5選舉區	中國國民黨	黃健豪	134706
臺中市第5選舉區	中華統一促進黨	林澤培	285
臺中市第5選舉區	司法改革黨	彭振芳	2647
臺中市第5選舉區	小民參政歐巴桑聯盟	蔡善雯	9266
臺中市第5選舉區	民主進步黨	莊競程	107357
臺中市第5選舉區	無	苗豐隆	718
臺中市第5選舉區	無	陳維新	4224
臺中市第5選舉區	臺灣雙語無法黨	謝旻汎	2113
臺中市第6選舉區	中國國民黨	羅廷瑋	103630
臺中市第6選舉區	中華統一促進黨	黃千庭	2091
臺中市第6選舉區	民主進步黨	江肇國	88674
臺中市第6選舉區	無	紀文清	1532
臺中市第6選舉區	無	賀姿華	2972
臺中市第7選舉區	中國國民黨	林家興	95549
臺中市第7選舉區	司法改革黨	林振東	5911
臺中市第7選舉區	民主進步黨	何欣純	132235
臺中市第8選舉區	中國國民黨	江啟臣	88651
臺中市第8選舉區	民主進步黨	謝志忠	64542
臺北市第1選舉區	中國國民黨	張斯綱	71837
臺北市第1選舉區	人民最大黨	張臺勝	161
臺北市第1選舉區	人民最大黨	胡金城	255
臺北市第1選舉區	人民民主黨	賴宗育	836
臺北市第1選舉區	民主進步黨	吳思瑤	91958
臺北市第1選舉區	無	侯漢廷	28510
臺北市第1選舉區	無	許盛鋒	231
臺北市第1選舉區	臺灣雙語無法黨	陳執中	950
臺北市第2選舉區	中國國民黨	游淑慧	69754
臺北市第2選舉區	中華統一促進黨	郭啟源	305
臺北市第2選舉區	人民最大黨	何梅娟	1741
臺北市第2選舉區	制度救世島	熊嘉玲	968
臺北市第2選舉區	民主進步黨	王世堅	111605
臺北市第3選舉區	中國國民黨	王鴻薇	105050
臺北市第3選舉區	人民最大黨	余新造	596
臺北市第3選舉區	制度救世島	高士恩	195
臺北市第3選舉區	台灣維新	楊時睿	1378
臺北市第3選舉區	民主進步黨	謝佩芬	89850
臺北市第3選舉區	無	陳源發	1851
臺北市第3選舉區	臺灣雙語無法黨	陳一郎	1107
臺北市第4選舉區	中國國民黨	李彥秀	112743
臺北市第4選舉區	制度救世島	黃啟彬	422
臺北市第4選舉區	台灣基進	吳欣岱	26382
臺北市第4選舉區	台灣整復師聯盟工黨	林秋彤	1881
臺北市第4選舉區	民主進步黨	高嘉瑜	95241
臺北市第5選舉區	中國國民黨	鍾小平	57634
臺北市第5選舉區	台灣麻將最大黨	張華特	692
臺北市第5選舉區	司法改革黨	李慧曦	1502
臺北市第5選舉區	合一行動聯盟	許敬民	174
臺北市第5選舉區	民主進步黨	吳沛憶	66932
臺北市第5選舉區	無	于美人	38913
臺北市第5選舉區	無	孫智麗	1489
臺北市第5選舉區	無	林志成	138
臺北市第5選舉區	無	陳燕玉	194
臺北市第5選舉區	經濟黨	蘇諍	472
臺北市第6選舉區	中國國民黨	羅智強	87973
臺北市第6選舉區	制度救世島	張雪卿	896
臺北市第6選舉區	台灣維新	朱翊銘	660
臺北市第6選舉區	社會民主黨	苗博雅	74375
臺北市第6選舉區	臺灣雙語無法黨	崔建章	2202
臺北市第7選舉區	中國國民黨	徐巧芯	89727
臺北市第7選舉區	中華愛國同心黨	李承龍	310
臺北市第7選舉區	台灣維新	羅丹	1073
臺北市第7選舉區	民主進步黨	許淑華	76113
臺北市第7選舉區	無	陳韋安	3286
臺北市第8選舉區	中國國民黨	賴士葆	87099
臺北市第8選舉區	台灣民眾黨	張其祿	28335
臺北市第8選舉區	台灣維新	劉佩玲	1122
臺北市第8選舉區	小民參政歐巴桑聯盟	賴宣任	6374
臺北市第8選舉區	民主進步黨	王閔生	59490
臺北市第8選舉區	無	夏萬浪	761
臺北市第8選舉區	無	張維學	201
臺北市第8選舉區	興中同盟會	胡之壯	136
臺南市第1選舉區	中國國民黨	周宏昌	49045
臺南市第1選舉區	中華統一促進黨	林芳竹	1603
臺南市第1選舉區	復康聯盟黨	蔡承攸	1305
臺南市第1選舉區	民主進步黨	賴惠員	96662
臺南市第1選舉區	無	侯陸太	2822
臺南市第1選舉區	無	魏耀乾	8978
臺南市第2選舉區	人民最大黨	詹秋嫻	3775
臺南市第2選舉區	民主進步黨	郭國文	97981
臺南市第2選舉區	無	陳昆和	76614
臺南市第3選舉區	中國國民黨	姚正玉	56348
臺南市第3選舉區	民主進步黨	陳亭妃	132377
臺南市第4選舉區	司法改革黨	劉清田	10082
臺南市第4選舉區	民主進步黨	林宜瑾	104688
臺南市第4選舉區	無	李全教	67357
臺南市第5選舉區	民主進步黨	林俊憲	126248
臺南市第5選舉區	臺灣雙語無法黨	蕭燐洪	38695
臺南市第6選舉區	中國國民黨	陳以信	64018
臺南市第6選舉區	民主進步黨	王定宇	89235
臺南市第6選舉區	無	陳永和	36985
臺東縣選舉區	中國國民黨	黃建賓	25778
臺東縣選舉區	小民參政歐巴桑聯盟	黃婉茹	1428
臺東縣選舉區	民主進步黨	賴坤成	23420
臺東縣選舉區	無	劉櫂豪	18744
臺東縣選舉區	無	許瑞貴	4522
臺東縣選舉區	無	陳長宏	211
花蓮縣選舉區	中國國民黨	傅崐萁	68786
花蓮縣選舉區	制度救世島	周玉梅	879
花蓮縣選舉區	民主進步黨	張美慧	51732
花蓮縣選舉區	無	許願神	6493
苗栗縣第1選舉區	民主進步黨	康世明	60358
苗栗縣第1選舉區	無	陳超明	79521
苗栗縣第2選舉區	中國國民黨	邱鎮軍	89111
苗栗縣第2選舉區	無	曾玟學	72749
連江縣選舉區	中國國民黨	陳雪生	3118
連江縣選舉區	台灣民眾黨	曹爾凱	1374
連江縣選舉區	民主進步黨	李問	1382
金門縣選舉區	中國國民黨	陳玉珍	28846
金門縣選舉區	台灣民眾黨	尚文凱	13177
金門縣選舉區	無	洪和成	2168
雲林縣第1選舉區	中國國民黨	丁學忠	84736
雲林縣第1選舉區	中華統一促進黨	郭炳宏	445
雲林縣第1選舉區	台灣革命黨	李昭儀	3072
雲林縣第1選舉區	民主進步黨	蘇治芬	81707
雲林縣第1選舉區	無	吳炳輝	1470
雲林縣第1選舉區	無	陳俊龍	5965
雲林縣第2選舉區	中國國民黨	邱良閱	78596
雲林縣第2選舉區	民主進步黨	劉建國	115376
高雄市第1選舉區	人民最大黨	劉承智	1596
高雄市第1選舉區	台灣民眾黨	曾尹儷	22169
高雄市第1選舉區	民主進步黨	邱議瑩	79567
高雄市第1選舉區	無	林義迪	42219
高雄市第2選舉區	中國國民黨	曹桓榮	68168
高雄市第2選舉區	民主進步黨	邱志偉	117992
高雄市第3選舉區	中國國民黨	李眉蓁	101513
高雄市第3選舉區	台灣麻將最大黨	郭璽	7147
高雄市第3選舉區	民主進步黨	李柏毅	108184
高雄市第3選舉區	無	張正達	1121
高雄市第3選舉區	無	陳銓霖	2549
高雄市第4選舉區	中國國民黨	陳若翠	64261
高雄市第4選舉區	民主進步黨	林岱樺	121001
高雄市第5選舉區	中國國民黨	黃柏霖	90046
高雄市第5選舉區	小民參政歐巴桑聯盟	張芳愉	12264
高雄市第5選舉區	民主進步黨	李昆澤	108735
高雄市第5選舉區	無	楊椒喬	3964
高雄市第6選舉區	中國國民黨	陳美雅	93750
高雄市第6選舉區	喜樂島聯盟	郭倍宏	15433
高雄市第6選舉區	民主進步黨	黃捷	113670
高雄市第7選舉區	中國國民黨	鍾易仲	89355
高雄市第7選舉區	司法改革黨	王和平統一	1141
高雄市第7選舉區	民主進步黨	許智傑	109484
高雄市第7選舉區	無	洪啟修	7978
高雄市第8選舉區	中國國民黨	李明璇	82602
高雄市第8選舉區	勞動黨	湛秀英	2876
高雄市第8選舉區	司法改革黨	李政憲	3087
高雄市第8選舉區	民主進步黨	賴瑞隆	121064
```

## 11. Write a SQL statement that is able to show the top 20 regional legislators **ELECTED** who received the most votes given `taiwan_election_2024.db`.

```
legislator_region	party	name	sum_votes
新北市第1選舉區	中國國民黨	洪孟楷	158596
臺中市第5選舉區	中國國民黨	黃健豪	134706
臺南市第3選舉區	民主進步黨	陳亭妃	132377
臺中市第7選舉區	民主進步黨	何欣純	132235
臺南市第5選舉區	民主進步黨	林俊憲	126248
新北市第11選舉區	中國國民黨	羅明才	123399
高雄市第8選舉區	民主進步黨	賴瑞隆	121064
高雄市第4選舉區	民主進步黨	林岱樺	121001
臺中市第4選舉區	中國國民黨	廖偉翔	119740
桃園市第4選舉區	中國國民黨	萬美玲	119430
臺中市第2選舉區	中國國民黨	顏寬恒	118962
新北市第2選舉區	民主進步黨	林淑芬	118544
高雄市第2選舉區	民主進步黨	邱志偉	117992
桃園市第1選舉區	中國國民黨	牛煦庭	116571
雲林縣第2選舉區	民主進步黨	劉建國	115376
高雄市第6選舉區	民主進步黨	黃捷	113670
臺北市第4選舉區	中國國民黨	李彥秀	112743
臺北市第2選舉區	民主進步黨	王世堅	111605
高雄市第7選舉區	民主進步黨	許智傑	109484
屏東縣第2選舉區	民主進步黨	徐富癸	108923
```

## 12. Write a SQL statement that is able to show all the regional legislators **ELECTED** given `taiwan_election_2024.db`.

```
legislator_region	party	name	sum_votes
南投縣第1選舉區	中國國民黨	馬文君	68890
南投縣第2選舉區	中國國民黨	游顥	70012
嘉義市選舉區	民主進步黨	王美惠	78069
嘉義縣第1選舉區	民主進步黨	蔡易餘	78551
嘉義縣第2選舉區	民主進步黨	陳冠廷	73598
基隆市選舉區	中國國民黨	林沛祥	91986
宜蘭縣選舉區	民主進步黨	陳俊宇	107308
屏東縣第1選舉區	民主進步黨	鍾佳濱	108723
屏東縣第2選舉區	民主進步黨	徐富癸	108923
彰化縣第1選舉區	民主進步黨	陳秀寳	98437
彰化縣第2選舉區	民主進步黨	黃秀芳	90688
彰化縣第3選舉區	中國國民黨	謝衣鳯	97681
彰化縣第4選舉區	民主進步黨	陳素月	97608
新北市第10選舉區	民主進步黨	吳琪銘	103437
新北市第11選舉區	中國國民黨	羅明才	123399
新北市第12選舉區	中國國民黨	廖先翔	92489
新北市第1選舉區	中國國民黨	洪孟楷	158596
新北市第2選舉區	民主進步黨	林淑芬	118544
新北市第3選舉區	民主進步黨	李坤城	100141
新北市第4選舉區	民主進步黨	吳秉叡	107772
新北市第5選舉區	民主進步黨	蘇巧慧	98586
新北市第6選舉區	民主進步黨	張宏陸	78847
新北市第7選舉區	中國國民黨	葉元之	78134
新北市第8選舉區	中國國民黨	張智倫	89808
新北市第9選舉區	中國國民黨	林德福	98260
新竹市選舉區	中國國民黨	鄭正鈐	92014
新竹縣第1選舉區	中國國民黨	徐欣瑩	84959
新竹縣第2選舉區	中國國民黨	林思銘	76608
桃園市第1選舉區	中國國民黨	牛煦庭	116571
桃園市第2選舉區	中國國民黨	涂權吉	103697
桃園市第3選舉區	中國國民黨	魯明哲	102056
桃園市第4選舉區	中國國民黨	萬美玲	119430
桃園市第5選舉區	中國國民黨	呂玉玲	89372
桃園市第6選舉區	中國國民黨	邱若華	81513
澎湖縣選舉區	民主進步黨	楊曜	24669
臺中市第1選舉區	民主進步黨	蔡其昌	79884
臺中市第2選舉區	中國國民黨	顏寬恒	118962
臺中市第3選舉區	中國國民黨	楊瓊瓔	106306
臺中市第4選舉區	中國國民黨	廖偉翔	119740
臺中市第5選舉區	中國國民黨	黃健豪	134706
臺中市第6選舉區	中國國民黨	羅廷瑋	103630
臺中市第7選舉區	民主進步黨	何欣純	132235
臺中市第8選舉區	中國國民黨	江啟臣	88651
臺北市第1選舉區	民主進步黨	吳思瑤	91958
臺北市第2選舉區	民主進步黨	王世堅	111605
臺北市第3選舉區	中國國民黨	王鴻薇	105050
臺北市第4選舉區	中國國民黨	李彥秀	112743
臺北市第5選舉區	民主進步黨	吳沛憶	66932
臺北市第6選舉區	中國國民黨	羅智強	87973
臺北市第7選舉區	中國國民黨	徐巧芯	89727
臺北市第8選舉區	中國國民黨	賴士葆	87099
臺南市第1選舉區	民主進步黨	賴惠員	96662
臺南市第2選舉區	民主進步黨	郭國文	97981
臺南市第3選舉區	民主進步黨	陳亭妃	132377
臺南市第4選舉區	民主進步黨	林宜瑾	104688
臺南市第5選舉區	民主進步黨	林俊憲	126248
臺南市第6選舉區	民主進步黨	王定宇	89235
臺東縣選舉區	中國國民黨	黃建賓	25778
花蓮縣選舉區	中國國民黨	傅崐萁	68786
苗栗縣第1選舉區	無	陳超明	79521
苗栗縣第2選舉區	中國國民黨	邱鎮軍	89111
連江縣選舉區	中國國民黨	陳雪生	3118
金門縣選舉區	中國國民黨	陳玉珍	28846
雲林縣第1選舉區	中國國民黨	丁學忠	84736
雲林縣第2選舉區	民主進步黨	劉建國	115376
高雄市第1選舉區	民主進步黨	邱議瑩	79567
高雄市第2選舉區	民主進步黨	邱志偉	117992
高雄市第3選舉區	民主進步黨	李柏毅	108184
高雄市第4選舉區	民主進步黨	林岱樺	121001
高雄市第5選舉區	民主進步黨	李昆澤	108735
高雄市第6選舉區	民主進步黨	黃捷	113670
高雄市第7選舉區	民主進步黨	許智傑	109484
高雄市第8選舉區	民主進步黨	賴瑞隆	121064
```

## 13. Based on the previous query result, write a SQL statement that is able to show all the regional legislators **ELECTED** from 中國國民黨 and 無(which means the elected legislator did not belong to any party).

```
legislator_region	party	name	sum_votes
南投縣第1選舉區	中國國民黨	馬文君	68890
南投縣第2選舉區	中國國民黨	游顥	70012
基隆市選舉區	中國國民黨	林沛祥	91986
彰化縣第3選舉區	中國國民黨	謝衣鳯	97681
新北市第11選舉區	中國國民黨	羅明才	123399
新北市第12選舉區	中國國民黨	廖先翔	92489
新北市第1選舉區	中國國民黨	洪孟楷	158596
新北市第7選舉區	中國國民黨	葉元之	78134
新北市第8選舉區	中國國民黨	張智倫	89808
新北市第9選舉區	中國國民黨	林德福	98260
新竹市選舉區	中國國民黨	鄭正鈐	92014
新竹縣第1選舉區	中國國民黨	徐欣瑩	84959
新竹縣第2選舉區	中國國民黨	林思銘	76608
桃園市第1選舉區	中國國民黨	牛煦庭	116571
桃園市第2選舉區	中國國民黨	涂權吉	103697
桃園市第3選舉區	中國國民黨	魯明哲	102056
桃園市第4選舉區	中國國民黨	萬美玲	119430
桃園市第5選舉區	中國國民黨	呂玉玲	89372
桃園市第6選舉區	中國國民黨	邱若華	81513
臺中市第2選舉區	中國國民黨	顏寬恒	118962
臺中市第3選舉區	中國國民黨	楊瓊瓔	106306
臺中市第4選舉區	中國國民黨	廖偉翔	119740
臺中市第5選舉區	中國國民黨	黃健豪	134706
臺中市第6選舉區	中國國民黨	羅廷瑋	103630
臺中市第8選舉區	中國國民黨	江啟臣	88651
臺北市第3選舉區	中國國民黨	王鴻薇	105050
臺北市第4選舉區	中國國民黨	李彥秀	112743
臺北市第6選舉區	中國國民黨	羅智強	87973
臺北市第7選舉區	中國國民黨	徐巧芯	89727
臺北市第8選舉區	中國國民黨	賴士葆	87099
臺東縣選舉區	中國國民黨	黃建賓	25778
花蓮縣選舉區	中國國民黨	傅崐萁	68786
苗栗縣第1選舉區	無	陳超明	79521
苗栗縣第2選舉區	中國國民黨	邱鎮軍	89111
連江縣選舉區	中國國民黨	陳雪生	3118
金門縣選舉區	中國國民黨	陳玉珍	28846
雲林縣第1選舉區	中國國民黨	丁學忠	84736
```

## 14. Write a SQL statement that is able to summarize the result of party legislators given `taiwan_election_2024.db`.

```
party	sum_votes
民主進步黨	4982062
中國國民黨	4764576
台灣民眾黨	3040615
時代力量	353412
小民參政歐巴桑聯盟	128613
台灣綠黨	117298
台灣基進	95078
親民黨	69818
臺灣雙語無法黨	44852
台灣團結聯盟	43375
新黨	40288
司法改革黨	37615
制度救世島	19665
中華統一促進黨	17423
人民最大黨	11746
台灣維新	10300
```

## 15. Based on the previous query result, write a SQL statement that is able to summarize the result of party legislators **EXCLUDING** the top three parties given `taiwan_election_2024.db`.

```
party	sum_votes
時代力量	353412
小民參政歐巴桑聯盟	128613
台灣綠黨	117298
台灣基進	95078
親民黨	69818
臺灣雙語無法黨	44852
台灣團結聯盟	43375
新黨	40288
司法改革黨	37615
制度救世島	19665
中華統一促進黨	17423
人民最大黨	11746
台灣維新	10300
```

## 16. Write a SQL statement that is able to summarize the presidential votes received by each candidate for each county given `taiwan_election_2024.db`.

```
county	name	sum_votes
南投縣	侯友宜/趙少康	109163
南投縣	賴清德/蕭美琴	103279
南投縣	柯文哲/吳欣盈	74854
嘉義市	賴清德/蕭美琴	68199
嘉義市	侯友宜/趙少康	49507
嘉義市	柯文哲/吳欣盈	39950
嘉義縣	賴清德/蕭美琴	139510
嘉義縣	侯友宜/趙少康	85642
嘉義縣	柯文哲/吳欣盈	67382
基隆市	侯友宜/趙少康	84507
基隆市	賴清德/蕭美琴	76079
基隆市	柯文哲/吳欣盈	58195
宜蘭縣	賴清德/蕭美琴	119517
宜蘭縣	侯友宜/趙少康	77441
宜蘭縣	柯文哲/吳欣盈	70171
屏東縣	賴清德/蕭美琴	226110
屏東縣	侯友宜/趙少康	146789
屏東縣	柯文哲/吳欣盈	103028
彰化縣	賴清德/蕭美琴	282514
彰化縣	侯友宜/趙少康	244140
彰化縣	柯文哲/吳欣盈	214714
新北市	賴清德/蕭美琴	948818
新北市	侯友宜/趙少康	864557
新北市	柯文哲/吳欣盈	645105
新竹市	賴清德/蕭美琴	92679
新竹市	柯文哲/吳欣盈	91384
新竹市	侯友宜/趙少康	82326
新竹縣	侯友宜/趙少康	126016
新竹縣	柯文哲/吳欣盈	120985
新竹縣	賴清德/蕭美琴	93309
桃園市	賴清德/蕭美琴	476441
桃園市	侯友宜/趙少康	460823
桃園市	柯文哲/吳欣盈	413528
澎湖縣	賴清德/蕭美琴	19023
澎湖縣	侯友宜/趙少康	18052
澎湖縣	柯文哲/吳欣盈	12202
臺中市	賴清德/蕭美琴	641622
臺中市	侯友宜/趙少康	552556
臺中市	柯文哲/吳欣盈	513025
臺北市	賴清德/蕭美琴	587899
臺北市	侯友宜/趙少康	587258
臺北市	柯文哲/吳欣盈	366854
臺南市	賴清德/蕭美琴	570811
臺南市	侯友宜/趙少康	286867
臺南市	柯文哲/吳欣盈	262560
臺東縣	侯友宜/趙少康	54220
臺東縣	賴清德/蕭美琴	30131
臺東縣	柯文哲/吳欣盈	25590
花蓮縣	侯友宜/趙少康	87953
花蓮縣	賴清德/蕭美琴	43157
花蓮縣	柯文哲/吳欣盈	43047
苗栗縣	侯友宜/趙少康	131230
苗栗縣	柯文哲/吳欣盈	95637
苗栗縣	賴清德/蕭美琴	91798
連江縣	侯友宜/趙少康	3860
連江縣	柯文哲/吳欣盈	1651
連江縣	賴清德/蕭美琴	648
金門縣	侯友宜/趙少康	28005
金門縣	柯文哲/吳欣盈	13038
金門縣	賴清德/蕭美琴	4569
雲林縣	賴清德/蕭美琴	169516
雲林縣	侯友宜/趙少康	111633
雲林縣	柯文哲/吳欣盈	99470
高雄市	賴清德/蕭美琴	800390
高雄市	侯友宜/趙少康	478476
高雄市	柯文哲/吳欣盈	358096
```

## 17. Based on the previous query result, write a SQL statement that is able to show the winner for each county.

```
county	winner	sum_votes
南投縣	侯友宜/趙少康	109163
嘉義市	賴清德/蕭美琴	68199
嘉義縣	賴清德/蕭美琴	139510
基隆市	侯友宜/趙少康	84507
宜蘭縣	賴清德/蕭美琴	119517
屏東縣	賴清德/蕭美琴	226110
彰化縣	賴清德/蕭美琴	282514
新北市	賴清德/蕭美琴	948818
新竹市	賴清德/蕭美琴	92679
新竹縣	侯友宜/趙少康	126016
桃園市	賴清德/蕭美琴	476441
澎湖縣	賴清德/蕭美琴	19023
臺中市	賴清德/蕭美琴	641622
臺北市	賴清德/蕭美琴	587899
臺南市	賴清德/蕭美琴	570811
臺東縣	侯友宜/趙少康	54220
花蓮縣	侯友宜/趙少康	87953
苗栗縣	侯友宜/趙少康	131230
連江縣	侯友宜/趙少康	3860
金門縣	侯友宜/趙少康	28005
雲林縣	賴清德/蕭美琴	169516
高雄市	賴清德/蕭美琴	800390
```

## 18. Write a SQL statement that is able to show the winner for each town in Taipei City(臺北市) given `taiwan_election_2024.db`.

```
county	town	winner	sum_votes
臺北市	中山區	賴清德/蕭美琴	54448
臺北市	中正區	侯友宜/趙少康	34733
臺北市	信義區	侯友宜/趙少康	53076
臺北市	內湖區	侯友宜/趙少康	64781
臺北市	北投區	賴清德/蕭美琴	61151
臺北市	南港區	侯友宜/趙少康	26529
臺北市	士林區	賴清德/蕭美琴	71869
臺北市	大同區	賴清德/蕭美琴	34270
臺北市	大安區	侯友宜/趙少康	72954
臺北市	文山區	侯友宜/趙少康	70844
臺北市	松山區	侯友宜/趙少康	47452
臺北市	萬華區	賴清德/蕭美琴	43369
```

## 19. Write a SQL statement that is able to show the winner for each town in the Six Capitals(臺北市、新北市、桃園市、臺中市、臺南市、高雄市) given `taiwan_election_2024.db`.

```
county	town	winner	sum_votes
新北市	三峽區	賴清德/蕭美琴	25489
新北市	三芝區	侯友宜/趙少康	5199
新北市	三重區	賴清德/蕭美琴	105117
新北市	中和區	侯友宜/趙少康	105887
新北市	五股區	賴清德/蕭美琴	22516
新北市	八里區	賴清德/蕭美琴	9714
新北市	土城區	賴清德/蕭美琴	57148
新北市	坪林區	賴清德/蕭美琴	2029
新北市	平溪區	賴清德/蕭美琴	1125
新北市	新店區	侯友宜/趙少康	87976
新北市	新莊區	賴清德/蕭美琴	105556
新北市	板橋區	賴清德/蕭美琴	139846
新北市	林口區	賴清德/蕭美琴	26957
新北市	樹林區	賴清德/蕭美琴	43632
新北市	永和區	侯友宜/趙少康	59409
新北市	汐止區	侯友宜/趙少康	48831
新北市	泰山區	賴清德/蕭美琴	18391
新北市	淡水區	侯友宜/趙少康	43837
新北市	深坑區	侯友宜/趙少康	5584
新北市	烏來區	侯友宜/趙少康	1604
新北市	瑞芳區	侯友宜/趙少康	8574
新北市	石碇區	賴清德/蕭美琴	2164
新北市	石門區	侯友宜/趙少康	2520
新北市	萬里區	賴清德/蕭美琴	5739
新北市	蘆洲區	賴清德/蕭美琴	52531
新北市	貢寮區	賴清德/蕭美琴	3396
新北市	金山區	賴清德/蕭美琴	5588
新北市	雙溪區	賴清德/蕭美琴	1925
新北市	鶯歌區	賴清德/蕭美琴	21041
桃園市	中壢區	侯友宜/趙少康	92934
桃園市	八德區	侯友宜/趙少康	43356
桃園市	大園區	賴清德/蕭美琴	20051
桃園市	大溪區	賴清德/蕭美琴	22229
桃園市	平鎮區	侯友宜/趙少康	48020
桃園市	復興區	侯友宜/趙少康	3222
桃園市	新屋區	賴清德/蕭美琴	12268
桃園市	桃園區	賴清德/蕭美琴	100081
桃園市	楊梅區	侯友宜/趙少康	36966
桃園市	蘆竹區	賴清德/蕭美琴	38760
桃園市	觀音區	賴清德/蕭美琴	17321
桃園市	龍潭區	侯友宜/趙少康	29087
桃園市	龜山區	賴清德/蕭美琴	38225
臺中市	中區	賴清德/蕭美琴	4022
臺中市	北屯區	賴清德/蕭美琴	64390
臺中市	南屯區	賴清德/蕭美琴	40321
臺中市	后里區	賴清德/蕭美琴	11661
臺中市	和平區	侯友宜/趙少康	3197
臺中市	外埔區	侯友宜/趙少康	6559
臺中市	大甲區	賴清德/蕭美琴	16754
臺中市	大肚區	賴清德/蕭美琴	12838
臺中市	大里區	賴清德/蕭美琴	48573
臺中市	大雅區	賴清德/蕭美琴	20480
臺中市	太平區	賴清德/蕭美琴	43029
臺中市	新社區	賴清德/蕭美琴	5571
臺中市	東勢區	侯友宜/趙少康	11876
臺中市	梧棲區	賴清德/蕭美琴	13515
臺中市	沙鹿區	賴清德/蕭美琴	20929
臺中市	清水區	賴清德/蕭美琴	21713
臺中市	潭子區	賴清德/蕭美琴	24934
臺中市	烏日區	賴清德/蕭美琴	18700
臺中市	石岡區	侯友宜/趙少康	3416
臺中市	神岡區	賴清德/蕭美琴	16636
臺中市	西區	賴清德/蕭美琴	27637
臺中市	西屯區	賴清德/蕭美琴	49613
臺中市	豐原區	賴清德/蕭美琴	40658
臺中市	霧峰區	賴清德/蕭美琴	15471
臺中市	龍井區	賴清德/蕭美琴	17219
臺北市	中山區	賴清德/蕭美琴	54448
臺北市	中正區	侯友宜/趙少康	34733
臺北市	信義區	侯友宜/趙少康	53076
臺北市	內湖區	侯友宜/趙少康	64781
臺北市	北投區	賴清德/蕭美琴	61151
臺北市	南港區	侯友宜/趙少康	26529
臺北市	士林區	賴清德/蕭美琴	71869
臺北市	大同區	賴清德/蕭美琴	34270
臺北市	大安區	侯友宜/趙少康	76394
臺北市	文山區	侯友宜/趙少康	70844
臺北市	松山區	侯友宜/趙少康	47452
臺北市	萬華區	賴清德/蕭美琴	43369
臺南市	七股區	賴清德/蕭美琴	7601
臺南市	下營區	賴清德/蕭美琴	7289
臺南市	中西區	賴清德/蕭美琴	23508
臺南市	仁德區	賴清德/蕭美琴	24021
臺南市	佳里區	賴清德/蕭美琴	19014
臺南市	六甲區	賴清德/蕭美琴	6882
臺南市	北區	賴清德/蕭美琴	69411
臺南市	北門區	賴清德/蕭美琴	3131
臺南市	南化區	賴清德/蕭美琴	2137
臺南市	南區	賴清德/蕭美琴	69988
臺南市	善化區	賴清德/蕭美琴	15541
臺南市	大內區	賴清德/蕭美琴	3191
臺南市	學甲區	賴清德/蕭美琴	8524
臺南市	安南區	賴清德/蕭美琴	61863
臺南市	安定區	賴清德/蕭美琴	10158
臺南市	安平區	賴清德/蕭美琴	19638
臺南市	官田區	賴清德/蕭美琴	7561
臺南市	將軍區	賴清德/蕭美琴	6699
臺南市	山上區	賴清德/蕭美琴	2289
臺南市	左鎮區	賴清德/蕭美琴	1482
臺南市	後壁區	賴清德/蕭美琴	7449
臺南市	新化區	賴清德/蕭美琴	13320
臺南市	新市區	賴清德/蕭美琴	11759
臺南市	新營區	賴清德/蕭美琴	19931
臺南市	東區	賴清德/蕭美琴	68864
臺南市	東山區	賴清德/蕭美琴	5772
臺南市	柳營區	賴清德/蕭美琴	6654
臺南市	楠西區	侯友宜/趙少康	2105
臺南市	歸仁區	賴清德/蕭美琴	22495
臺南市	永康區	賴清德/蕭美琴	66181
臺南市	玉井區	賴清德/蕭美琴	3349
臺南市	白河區	賴清德/蕭美琴	8608
臺南市	西港區	賴清德/蕭美琴	8928
臺南市	關廟區	賴清德/蕭美琴	11619
臺南市	鹽水區	賴清德/蕭美琴	7882
臺南市	麻豆區	賴清德/蕭美琴	16080
臺南市	龍崎區	賴清德/蕭美琴	1243
高雄市	三民區	賴清德/蕭美琴	100125
高雄市	仁武區	賴清德/蕭美琴	28972
高雄市	內門區	賴清德/蕭美琴	3976
高雄市	六龜區	賴清德/蕭美琴	2972
高雄市	前金區	賴清德/蕭美琴	8448
高雄市	前鎮區	賴清德/蕭美琴	55508
高雄市	大寮區	賴清德/蕭美琴	33642
高雄市	大樹區	賴清德/蕭美琴	13685
高雄市	大社區	賴清德/蕭美琴	11133
高雄市	小港區	賴清德/蕭美琴	45675
高雄市	岡山區	賴清德/蕭美琴	26882
高雄市	左營區	賴清德/蕭美琴	48791
高雄市	彌陀區	賴清德/蕭美琴	5672
高雄市	新興區	賴清德/蕭美琴	15007
高雄市	旗山區	賴清德/蕭美琴	10321
高雄市	旗津區	賴清德/蕭美琴	8702
高雄市	杉林區	賴清德/蕭美琴	2767
高雄市	林園區	賴清德/蕭美琴	21587
高雄市	桃源區	侯友宜/趙少康	1186
高雄市	梓官區	賴清德/蕭美琴	12115
高雄市	楠梓區	賴清德/蕭美琴	51318
高雄市	橋頭區	賴清德/蕭美琴	14401
高雄市	永安區	賴清德/蕭美琴	4334
高雄市	湖內區	賴清德/蕭美琴	9463
高雄市	燕巢區	賴清德/蕭美琴	9234
高雄市	田寮區	賴清德/蕭美琴	2419
高雄市	甲仙區	賴清德/蕭美琴	1294
高雄市	美濃區	賴清德/蕭美琴	9157
高雄市	苓雅區	賴清德/蕭美琴	48667
高雄市	茂林區	侯友宜/趙少康	660
高雄市	茄萣區	賴清德/蕭美琴	9551
高雄市	路竹區	賴清德/蕭美琴	15149
高雄市	那瑪夏區	侯友宜/趙少康	922
高雄市	阿蓮區	賴清德/蕭美琴	9111
高雄市	鳥松區	賴清德/蕭美琴	14360
高雄市	鳳山區	賴清德/蕭美琴	98990
高雄市	鹽埕區	賴清德/蕭美琴	7835
高雄市	鼓山區	賴清德/蕭美琴	38328
```

## 20. Write a SQL statement that is able to summarize the votes received in 3 types of elections for the 3 major parties in 2024 given `taiwan_election_2024.db`.

```
election_type	name	sum_votes
不分區立委	中國國民黨	4764576
不分區立委	台灣民眾黨	3040615
不分區立委	民主進步黨	4982062
區域立委	中國國民黨	5401933
區域立委	台灣民眾黨	397214
區域立委	民主進步黨	6035971
總統/副總統	中國國民黨	4671021
總統/副總統	台灣民眾黨	3690466
總統/副總統	民主進步黨	5586019
```