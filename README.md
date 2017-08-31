#	Line Stack
I.	Jenis Chart : Line

II.	Option: 
1.	title : text (string) : untuk membuat judul pada echart
2.	title: subtext (string) : support untuk membuat garis baru
3.	title: sublink (string) : text yang support untuk hyperlink
4.	title : link (string) : untuk berpindahan halaman dengan menggunakan text.
5.	title : padding (number) : membuat ruang di sekitar text.
6.	title : backgroundColor (color) : mengubah warna belakang sebuah objek.
7.	title : borderColor (color) : mengubah warna area pinggir pada objek.
8.	title : shadowBlur (number) : membuat bayangan objek menjadi blur.
9.	title : shadowColor (color) : mengubah warna bayangan objek.
10.	title : shadowOffsetX (number) : jarak bayangan horizontal.
11.	title : shadowOffsetY (number) : jarak bayangan vertikal.
12.	title : textAlign (string) : menentukan posisi huruf (left,center,right).
13.	title : textBaseLine (string) : mengatur posisi text dalam vertical (middle,top,bottom).
14.	title : textStyle : color(string) : untuk mengubah warna pada text.
15.	title : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
16.	title : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
17.	title : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
18.	title : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
19.	title : textStyle : fontFamily (string) : mengubah jenis font.
20.	legend : left (string,number) : jarak objek dari sebelah kiri.
21.	legend : right (string,number) : jarak objek dari sebelah kanan.
22.	legend : top (string,number) : jarak objek dari sebelah atas.
23.	legend : bottom (string,number) : jarak objek dari sebelah bawah.
24.	legend : width (string,number) : menentukan lebar komponen legend.
25.	legend : height (string,number) : menentukan panjang komponen legend.
26.	legend : orient (string) : mengatur letak orientasi legend (horizontal,vertical).
27.	legend : align (string) : menentukan posisi text (auto,left,right).
28.	legend : padding (number) : membuat ruang di sekitar text.
29.	legend : itemGap (number) : jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical dalam tata letak vertical.
30.	legend : itemWidth (number) : lebar gambar simbol legend.
31.	legend : itemHeight (number) : panjang gambar simbol legend.
32.	legend : formatter (string,function) : formatter digunakan untuk memformat label legend, yang mendukung template string dan function callback.
33.	legend : selectedMode (string,boolean) : mode legend yang dipilih, yang mengontrol apakah sama dapat ditampilkan secara bergantian dengan mengklik salah satu legend (single,multiple).
34.	legend : inactiveColor (color) : warna legend pada saat tidak aktif.
35.	legend : textStyle : color(string) : untuk mengubah warna pada text.
36.	legend : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
37.	legend : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
38.	legend : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
39.	legend : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
40.	legend : textStyle : fontFamily (string) : mengubah jenis font.
41.	legend : backgroundColor (color) : mengubah warna belakang sebuah objek.
42.	legend : borderColor (color) : mengubah warna area pinggir pada objek.
43.	legend : shadowBlur (number) : membuat bayangan objek menjadi blur.
44.	legend : shadowColor (color) : mengubah warna bayangan objek.
45.	legend : shadowOffsetX (number) : jarak bayangan horizontal.
46.	legend : shadowOffsetY (number) : jarak bayangan vertikal.
47.	tooltip: trigger (string)axis : untuk chart yang mempunyai kategori, seperti bar charts/line charts.
48.	tooltip: trigger (string)item : untuk chart yang tidak memiliki kategori,seperti scatter chart/pie chart.
49.	tooltip: trigger (string)none : untuk tidak menampilkan kategori.
50.	tooltip : axisPointer (object) : type (string)  : item konfigurasi untuk indikator axis (line,shadow,cross).
51.	legend : data(object/array) : item array biasanya merupakan nama yang mewakili string.
52.	grid : left(string/number) : jarak antara komponen grid dan sisi kiri.
53.	grid : right(string/number) : jarak antara komponen grid dan sisi kanan.
54.	grid : bottom(string/number) : jarak antara komponen grid dan sisi bawah.
55.	grid : top(string/number) : jarak antara komponen grid dan sisi atas.
56.	grid : tooltip: trigger (string)axis : untuk chart yang mempunyai kategori, seperti bar charts/line charts.
57.	grid : tooltip: trigger (string)item : untuk chart yang tidak memiliki kategori,seperti scatter chart/pie chart.
58.	grid : tooltip: trigger (string)none : untuk tidak menampilkan kategori.
59.	grid : tooltip : axisPointer (object) : type (string)  : item konfigurasi untuk indikator axis (line,shadow,cross).
60.	grid : tooltip : formatter (string,function) : formatter dari layer floating tooltip yang mendukung template string dan fungsi callback.
61.	grid : containLabel(boolean) : daerah grid mengandung label sumbu.
62.	grid  : borderColor (color) : mengubah warna area pinggir pada objek.
63.	grid : shadowBlur (number) : membuat bayangan objek menjadi blur.
64.	grid : shadowColor (color) : mengubah warna bayangan objek.
65.	grid : shadowOffsetX (number) : jarak bayangan horizontal.
66.	grid : shadowOffsetY (number) : jarak bayangan vertikal.
67.	grid : tooltip : padding (number) : membuat ruang di sekitar text.
68.	grid : tooltip : textStyle : color(string) : untuk mengubah warna pada text.
69.	grid : tooltip : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
70.	grid : tooltip : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
71.	grid : tooltip : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
72.	grid : tooltip : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
73.	grid : tooltip : textStyle : fontFamily (string) : mengubah jenis font.
74.	toolbox : feature(object) : saveImage(object) : untuk save gambar.
75.	xAxis : type(string) : type dari axis(value,category,time,log).
76.	xAxis : boundaryGap(boolean,array) : batas pada kedua sisi sumbu koordinat. Pengaturan sumbu kategori dan sumbu non-kategori berbeda.
77.	xAxis : position (string) : posisi sumbu xAxis.
78.	xAxis : offset (number) : sumbu x relatif terhadap posisi default. Bisa berguna juga bila multiple xAxis memiliki nilai posisi yang sama.
79.	xAxis : name (string) : membuat text pada sumbu xAxis.
80.	xAxis : nameLocation (string) : menentukan posisi text pada sumbu xAxis (start,middle,end).
81.	xAxis : nameTextStyle : color(string) : untuk mengubah warna pada text.
82.	xAxis : nameTextStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
83.	xAxis : nameTextStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
84.	xAxis : nameTextStyle : fontWeight (string) : bold : membuat text menjadi tebal.
85.	xAxis : nameTextStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
86.	xAxis : nameTextStyle : fontFamily (string) : mengubah jenis font.
87.	xAxis : nameGap (number) : celah antara nama sumbu dan garis sumbu.
88.	xAxis : nameRotate (number) : rotasi nama sumbu.
89.	xAxis : inverse (boolean) : sumbu yang terbalik.
90.	xAxis : min (number,string) : minimum value sumbu.
91.	xAxis : max (number,string) : maxsimum value sumbu.
92.	xAxis : scale (boolean) : ini hanya tersedia dalam axis numerik, yaitu, type: 'value.
konfigurasi ini tidak tersedia saat min dan max ditetapkan.
93.	xAxis : data(object) : data kategori, tersedia dalam type 'category' axis.
94.	xAxis : axisLine (object) : show (boolean) : memunculkan garis sumbu (true) atau tidak memunculkan garis sumbu (false).
95.	xAxis : axisLine (object) : onZero (boolean) : menentukan sumbu X atau Y terletak pada posisi asal yang lain, dimana value 0 pada sumbu. Berlaku hanya jika sumbu yang lain adalah value type, dan mempunyai value 0 (default=true).
96.	xAxis : axisLine (object) : lineStyle (color) : warna pada garis.
97.	xAxis : axisLine (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
98.	xAxis : axisLine (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
99.	xAxis : axisLine (object) : shadowColor (color) : mengubah warna bayangan objek.
100.	xAxis : axisLine (object) : shadowOffsetX (number) : jarak bayangan horizontal.
101.	xAxis : axisLine (object) : shadowOffsetY (number) : jarak bayangan vertikal.
102.	xAxis : axisTick (object) : show (boolean) : untuk menunjukkan tanda sumbu.
103.	xAxis : axisTick (object) : alignWithLabel (boolean) : sejajarkan sumbu dengan label, yang tersedia hanya jika boundaryGap diset menjadi true dalam sumbu kategori.
104.	xAxis : axisLabel (object) : rotate (number) : untuk merotasikan label pada axis.
105.	xAxis : axisLabel (object) : margin (number) : margin antara axis label dan garis sumbu.
106.	xAxis : axisLabel (object) : formatter (string,function) : Formatter dari label sumbu, yang mendukung template string dan fungsi callback. 
107.	xAxis : axisLabel (object) : textStyle (object) : color(string) : untuk mengubah warna pada text.
108.	xAxis : axisLabel (object) : textStyle (object) : fontSize(number) : untuk mengubah ukuran text (default=18).
109.	xAxis : axisLabel (object) : textStyle (object) : fontStyle(string) : italic : mengubah huruf menjadi miring.
110.	xAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : bold : membuat text menjadi tebal.
111.	xAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : lighter : membuat text menjadi tipis.
112.	xAxis : axisLabel (object) : textStyle (object) : fontFamily (string) : mengubah jenis font.
113.	xAxis : align (string) : menentukan posisi huruf (left,center,right).
114.	xAxis : axisLabel (object) : textStyle (object) : baseLine (string) : textStyle (object) : mengatur posisi text dalam vertical (middle,top,bottom).
115.	xAxis : splitLine (object) : show (boolean)  :  nilai sumbu ditampilkan secara default, sedangkan sumbu kategori tidak.
116.	xAxis : splitLine (object) : lineStyle (object) : interval (number,function) : garis pada chart.
117.	xAxis : splitLine (object) : lineStyle (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
118.	xAxis : splitLine (object) : lineStyle (object) : shadowColor (color) : mengubah warna bayangan objek.
119.	xAxis : splitLine (object) : lineStyle (object) : shadowOffsetX (number) : jarak bayangan horizontal.
120.	xAxis : splitLine (object) : lineStyle (object) : shadowOffsetY (number) : jarak bayangan vertikal.
121.	xAxis : splitLine (object) : lineStyle (object) : color(string) : untuk mengubah warna pada text.
122.	xAxis : splitLine (object) : lineStyle (object) : width (number) : lebar splitLine.
123.	xAxis : splitLine (object) : lineStyle (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
124.	yAxis : type(string) : type dari axis(value,category,time,log).
125.	yAxis : boundaryGap(boolean,array) : batas pada kedua sisi sumbu koordinat. Pengaturan sumbu kategori dan sumbu non-kategori berbeda.
126.	yAxis : position (string) : posisi sumbu yAxis.
127.	yAxis : offset (number) : sumbu y relatif terhadap posisi default. Bisa berguna juga bila multiple yAxis memiliki nilai posisi yang sama.
128.	yAxis : name (string) : membuat text pada sumbu xAxis.
129.	yAxis : nameLocation (string) : menentukan posisi text pada sumbu xAxis (start,middle,end).
130.	yAxis : nameTextStyle : color(string) : untuk mengubah warna pada text.
131.	yAxis : nameTextStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
132.	yAxis : nameTextStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
133.	yAxis : nameTextStyle : fontWeight (string) : bold : membuat text menjadi tebal.
134.	yAxis : nameTextStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
135.	yAxis : nameTextStyle : fontFamily (string) : mengubah jenis font.
136.	yAxis : nameGap (number) : celah antara nama sumbu dan garis sumbu.
137.	yAxis : nameRotate (number) : rotasi nama sumbu.
138.	yAxis : inverse (boolean) : sumbu yang terbalik.
139.	yAxis : min (number,string) : minimum value sumbu.
140.	yAxis : max (number,string) : maxsimum value sumbu.
141.	yAxis : scale (boolean) : ini hanya tersedia dalam axis numerik, yaitu, type: 'value.
142.	konfigurasi ini tidak tersedia saat min dan max ditetapkan.
143.	yAxis : data(object) : data kategori, tersedia dalam type 'category' axis.
144.	yAxis : axisLine (object) : show (boolean) : memunculkan garis sumbu (true) atau tidak memunculkan garis sumbu (false).
145.	yAxis : axisLine (object) : onZero (boolean) : menentukan sumbu X atau Y terletak pada posisi asal yang lain, dimana value 0 pada sumbu. Berlaku hanya jika sumbu yang lain adalah value type, dan mempunyai value 0 (default=true).
146.	yAxis : axisLine (object) : lineStyle (color) : warna pada garis.
147.	yAxis : axisLine (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
148.	yAxis : axisLine (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
149.	yAxis : axisLine (object) : shadowColor (color) : mengubah warna bayangan objek.
150.	yAxis : axisLine (object) : shadowOffsetX (number) : jarak bayangan horizontal.
151.	yAxis : axisLine (object) : shadowOffsetY (number) : jarak bayangan vertikal.
152.	yAxis : axisTick (object) : show (boolean) : untuk menunjukkan tanda sumbu.
153.	yAxis : axisTick (object) : alignWithLabel (boolean) : sejajarkan sumbu dengan label, yang tersedia hanya jika boundaryGap diset menjadi true dalam sumbu kategori.
154.	yAxis : axisLabel (object) : rotate (number) : untuk merotasikan label pada axis.
155.	yAxis : axisLabel (object) : margin (number) : margin antara axis label dan garis sumbu.
156.	yAxis : axisLabel (object) : formatter (string,function) : Formatter dari label sumbu, yang mendukung template string dan fungsi callback.
157.	yAxis : axisLabel (object) : 
158.	yAxis : axisLabel (object) : textStyle (object) : color(string) : untuk mengubah warna pada text.
159.	yAxis : axisLabel (object) : textStyle (object) : fontSize(number) : untuk mengubah ukuran text (default=18).
160.	yAxis : axisLabel (object) : textStyle (object) : fontStyle(string) : italic : mengubah huruf menjadi miring.
161.	yAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : bold : membuat text menjadi tebal.
162.	yAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : lighter : membuat text menjadi tipis.
163.	yAxis : axisLabel (object) : textStyle (object) : fontFamily (string) : mengubah jenis font.
164.	yAxis : align (string) : menentukan posisi huruf (left,center,right).
165.	yAxis : axisLabel (object) : textStyle (object) : baseLine (string) : textStyle (object) : mengatur posisi text dalam vertical (middle,top,bottom).
166.	yAxis : splitLine (object) : show (boolean)  :  nilai sumbu ditampilkan secara default, sedangkan sumbu kategori tidak.
167.	yAxis : splitLine (object) : lineStyle (object) : interval (number,function) : garis pada chart.
168.	yAxis : splitLine (object) : lineStyle (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
169.	yAxis : splitLine (object) : lineStyle (object) : shadowColor (color) : mengubah warna bayangan objek.
170.	yAxis : splitLine (object) : lineStyle (object) : shadowOffsetX (number) : jarak bayangan horizontal.
171.	yAxis : splitLine (object) : lineStyle (object) : shadowOffsetY (number) : jarak bayangan vertikal.
172.	yAxis : splitLine (object) : lineStyle (object) : color(string) : untuk mengubah warna pada text.
173.	yAxis : splitLine (object) : lineStyle (object) : width (number) : lebar splitLine.
174.	yAxis : splitLine (object) : lineStyle (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
175.	yAxis : splitNumber (number) : jumlah segmen yang menjadi terpecah.
Perhatikan bahwa nomor ini hanya berfungsi sebagai rekomendasi, dan segmen sebenarnya dapat disesuaikan berdasarkan keterbacaan. 
 tidak tersedia untuk axis type ‘category’.
176.	series (object) : name(string) : penamaan pada array. 
177.	textStyle : color(string) : untuk mengubah warna pada text.
178.	textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
179.	textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
180.	textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
181.	textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
182.	textStyle : fontFamily (string) : mengubah jenis font.
