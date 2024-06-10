# IMAD-practicum
ST10389533
McAnthony Anowi


<?xml version="1.0" encoding="utf-8"?>
2    <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
3        xmlns:app="http://schemas.android.com/apk/res-auto"
4        xmlns:tools="http://schemas.android.com/tools"
5        android:layout_width="match_parent"
6        android:layout_height="match_parent"
7        android:background="#4C95CF"
8        android:backgroundTint="#4FA0C5"
9        tools:context=".MainActivity">
10   
11       <TextView
12           android:id="@+id/textView"
13           android:layout_width="wrap_content"
14           android:layout_height="wrap_content"
15           android:text="WEATHER APP"
16           android:textSize="34sp"
17           android:textStyle="bold"
18           app:layout_constraintBottom_toBottomOf="parent"
19           app:layout_constraintEnd_toEndOf="parent"
20           app:layout_constraintHorizontal_bias="0.497"
21           app:layout_constraintStart_toStartOf="parent"
22           app:layout_constraintTop_toTopOf="parent"
23           app:layout_constraintVertical_bias="0.339" />
24   
25       <ImageView
26           android:id="@+id/imageView"
27           android:layout_width="299dp"
28           android:layout_height="210dp"
29           android:layout_marginEnd="56dp"
30           app:layout_constraintEnd_toEndOf="parent"
31           app:layout_constraintTop_toTopOf="parent"
32           app:srcCompat="@drawable/_32383" />
33   
34       <ImageView
35           android:id="@+id/imageView4"
36           android:layout_width="39dp"
37           android:layout_height="54dp"
38           android:layout_marginEnd="300dp"
39           app:layout_constraintBottom_toBottomOf="parent"
40           app:layout_constraintEnd_toEndOf="@+id/imageView"
41           app:layout_constraintTop_toTopOf="parent"
42           app:layout_constraintVertical_bias="0.023"
43           app:srcCompat="@drawable/exit_icon_png_5" />
44   
45       <TextView
46           android:id="@+id/textView2"
47           android:layout_width="wrap_content"
48           android:layout_height="wrap_content"
49           android:text="13℃"
50           android:textSize="34sp"
51           android:textStyle="bold"
52           app:layout_constraintBottom_toBottomOf="parent"
53           app:layout_constraintEnd_toEndOf="parent"
54           app:layout_constraintStart_toStartOf="parent"
55           app:layout_constraintTop_toTopOf="parent" />
56   
57       <TextView
58           android:id="@+id/textView3"
59           android:layout_width="wrap_content"
60           android:layout_height="wrap_content"
61           android:layout_marginTop="400dp"
62           android:text="Cloudy"
63           android:textSize="24sp"
64           app:layout_constraintEnd_toEndOf="parent"
65           app:layout_constraintHorizontal_bias="0.498"
66           app:layout_constraintStart_toStartOf="parent"
67           app:layout_constraintTop_toTopOf="parent" />
68   
69       <ImageView
70           android:id="@+id/imageView5"
71           android:layout_width="121dp"
72           android:layout_height="104dp"
73           android:layout_marginTop="420dp"
74           app:layout_constraintEnd_toEndOf="parent"
75           app:layout_constraintStart_toStartOf="parent"
76           app:layout_constraintTop_toTopOf="parent"
77           app:srcCompat="@drawable/weather03_512" />
78   
79       <TextView
80           android:id="@+id/textView4"
81           android:layout_width="wrap_content"
82           android:layout_height="wrap_content"
83           android:layout_marginBottom="136dp"
84           android:text="McAnthony Junior Anowi"
85           android:textSize="20sp"
86           app:layout_constraintBottom_toBottomOf="parent"
87           app:layout_constraintEnd_toEndOf="parent"
88           app:layout_constraintHorizontal_bias="0.085"
89           app:layout_constraintStart_toStartOf="parent" />
90   
91       <TextView
92           android:id="@+id/textView5"
93           android:layout_width="wrap_content"
94           android:layout_height="wrap_content"
95           android:layout_marginBottom="92dp"
96           android:text="ST10389533"
97           android:textSize="20sp"
98           app:layout_constraintBottom_toBottomOf="parent"
99           app:layout_constraintEnd_toEndOf="parent"
100          app:layout_constraintHorizontal_bias="0.054"
101          app:layout_constraintStart_toStartOf="parent" />
102  
103      <Button
104          android:id="@+id/forecast"
105          android:layout_width="113dp"
106          android:layout_height="52dp"
107          android:layout_marginEnd="40dp"
108          android:layout_marginBottom="40dp"
109          android:text="Forecasts"
110          android:textColorHighlight="#D5BABA"
111          android:textColorLink="#A38383"
112          android:textIsSelectable="false"
113          android:textSize="14sp"
114          app:layout_constraintBottom_toBottomOf="parent"
115          app:layout_constraintEnd_toEndOf="parent" />
116  
117  </androidx.constraintlayout.widget.ConstraintLayout>

 <?xml version="1.0" encoding="utf-8"?>
2    <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
3        xmlns:app="http://schemas.android.com/apk/res-auto"
4        xmlns:tools="http://schemas.android.com/tools"
5        android:layout_width="match_parent"
6        android:layout_height="match_parent"
7        android:background="#448AFF">
8    
9        <ImageView
10           android:id="@+id/imageView2"
11           android:layout_width="39dp"
12           android:layout_height="35dp"
13           android:layout_marginEnd="356dp"
14           app:layout_constraintBottom_toBottomOf="parent"
15           app:layout_constraintEnd_toEndOf="parent"
16           app:layout_constraintTop_toTopOf="parent"
17           app:layout_constraintVertical_bias="0.022"
18           app:srcCompat="@drawable/arrow_back" />
19   
20       <ImageView
21           android:id="@+id/imageView3"
22           android:layout_width="363dp"
23           android:layout_height="216dp"
24           app:layout_constraintBottom_toBottomOf="parent"
25           app:layout_constraintEnd_toEndOf="parent"
26           app:layout_constraintHorizontal_bias="0.666"
27           app:layout_constraintStart_toStartOf="parent"
28           app:layout_constraintTop_toTopOf="parent"
29           app:layout_constraintVertical_bias="0.11"
30           app:srcCompat="@drawable/cloudddddd" />
31   
32       <TextView
33           android:id="@+id/temp_wednesday"
34           android:layout_width="wrap_content"
35           android:layout_height="wrap_content"
36           android:layout_marginStart="16dp"
37           android:layout_marginBottom="20dp"
38           android:text="WEDNESDAY:"
39           android:textSize="20sp"
40           app:layout_constraintBottom_toTopOf="@+id/temp_thursday"
41           app:layout_constraintStart_toStartOf="parent" />
42   
43       <TextView
44           android:id="@+id/temp_thursday"
45           android:layout_width="wrap_content"
46           android:layout_height="wrap_content"
47           android:layout_marginStart="16dp"
48           android:layout_marginBottom="20dp"
49           android:text="THURSDAY:"
50           android:textSize="20sp"
51           app:layout_constraintBottom_toTopOf="@+id/temp_friday"
52           app:layout_constraintStart_toStartOf="parent" />
53   
54       <TextView
55           android:id="@+id/temp_friday"
56           android:layout_width="wrap_content"
57           android:layout_height="wrap_content"
58           android:layout_marginBottom="20dp"
59           android:text="FRIDAY:"
60           android:textSize="20sp"
61           app:layout_constraintBottom_toTopOf="@+id/temp_saturday"
62           app:layout_constraintEnd_toEndOf="parent"
63           app:layout_constraintHorizontal_bias="0.047"
64           app:layout_constraintStart_toStartOf="parent" />
65   
66       <TextView
67           android:id="@+id/temp_saturday"
68           android:layout_width="wrap_content"
69           android:layout_height="wrap_content"
70           android:layout_marginBottom="36dp"
71           android:text="SATURDAY:"
72           android:textSize="20sp"
73           app:layout_constraintBottom_toTopOf="@+id/temp_sunday"
74           app:layout_constraintEnd_toEndOf="parent"
75           app:layout_constraintHorizontal_bias="0.052"
76           app:layout_constraintStart_toStartOf="parent" />
77   
78       <TextView
79           android:id="@+id/temp_monday"
80           android:layout_width="wrap_content"
81           android:layout_height="wrap_content"
82           android:layout_marginStart="16dp"
83           android:layout_marginBottom="28dp"
84           android:text="MONDAY:"
85           android:textSize="20sp"
86           app:layout_constraintBottom_toTopOf="@+id/temp_tuesday"
87           app:layout_constraintStart_toStartOf="parent" />
88   
89       <TextView
90           android:id="@+id/temp_tuesday"
91           android:layout_width="wrap_content"
92           android:layout_height="wrap_content"
93           android:layout_marginStart="16dp"
94           android:layout_marginBottom="20dp"
95           android:text="TUESDAY:"
96           android:textSize="20sp"
97           app:layout_constraintBottom_toTopOf="@+id/temp_wednesday"
98           app:layout_constraintStart_toStartOf="parent" />
99   
100      <TextView
101          android:id="@+id/temp_sunday"
102          android:layout_width="wrap_content"
103          android:layout_height="wrap_content"
104          android:layout_marginBottom="124dp"
105          android:text="SUNDAY:"
106          android:textSize="20sp"
107          app:layout_constraintBottom_toBottomOf="parent"
108          app:layout_constraintEnd_toEndOf="parent"
109          app:layout_constraintHorizontal_bias="0.048"
110          app:layout_constraintStart_toStartOf="parent" />
111  
112      <EditText
113          android:id="@+id/temp2"
114          android:layout_width="wrap_content"
115          android:layout_height="wrap_content"
116          android:ems="10"
117          android:gravity="start|top"
118          android:inputType="textMultiLine"
119          app:layout_constraintBottom_toBottomOf="@+id/temp_tuesday"
120          app:layout_constraintEnd_toEndOf="parent"
121          app:layout_constraintStart_toStartOf="@+id/temp_tuesday"
122          app:layout_constraintTop_toTopOf="@+id/temp_tuesday" />
123  
124      <EditText
125          android:id="@+id/temp1"
126          android:layout_width="wrap_content"
127          android:layout_height="wrap_content"
128          android:ems="10"
129          android:gravity="start|top"
130          android:inputType="textMultiLine"
131          tools:layout_editor_absoluteX="110dp"
132          tools:layout_editor_absoluteY="274dp" />
133  
134      <Button
135          android:id="@+id/button2"
136          android:layout_width="wrap_content"
137          android:layout_height="wrap_content"
138          android:text="DAILY REPORTS"
139          tools:layout_editor_absoluteX="245dp"
140          tools:layout_editor_absoluteY="16dp" />
141  
142      <EditText
143          android:id="@+id/temp3"
144          android:layout_width="wrap_content"
145          android:layout_height="wrap_content"
146          android:ems="10"
147          android:gravity="start|top"
148          android:inputType="textMultiLine"
149          app:layout_constraintBottom_toBottomOf="@+id/temp_wednesday"
150          app:layout_constraintEnd_toEndOf="parent"
151          app:layout_constraintHorizontal_bias="0.664"
152          app:layout_constraintStart_toStartOf="@+id/temp_wednesday"
153          app:layout_constraintTop_toTopOf="@+id/temp_wednesday"
154          app:layout_constraintVertical_bias="0.611" />
155  
156      <EditText
157          android:id="@+id/temp4"
158          android:layout_width="wrap_content"
159          android:layout_height="wrap_content"
160          android:layout_marginStart="112dp"
161          android:ems="10"
162          android:gravity="start|top"
163          android:inputType="textMultiLine"
164          app:layout_constraintBottom_toBottomOf="@+id/temp_thursday"
165          app:layout_constraintStart_toStartOf="@+id/temp_thursday"
166          app:layout_constraintTop_toTopOf="@+id/temp_thursday"
167          app:layout_constraintVertical_bias="0.555" />
168  
169      <EditText
170          android:id="@+id/temp5"
171          android:layout_width="wrap_content"
172          android:layout_height="wrap_content"
173          android:ems="10"
174          android:gravity="start|top"
175          android:inputType="textMultiLine"
176          tools:layout_editor_absoluteX="88dp"
177          tools:layout_editor_absoluteY="457dp" />
178  
179      <EditText
180          android:id="@+id/temp6"
181          android:layout_width="wrap_content"
182          android:layout_height="wrap_content"
183          android:ems="10"
184          android:gravity="start|top"
185          android:inputType="textMultiLine"
186          tools:layout_editor_absoluteX="123dp"
187          tools:layout_editor_absoluteY="502dp" />
188  
189      <EditText
190          android:id="@+id/temp7"
191          android:layout_width="wrap_content"
192          android:layout_height="wrap_content"
193          android:ems="10"
194          android:gravity="start|top"
195          android:inputType="textMultiLine"
196          app:layout_constraintBottom_toBottomOf="@+id/temp_sunday"
197          app:layout_constraintEnd_toEndOf="parent"
198          app:layout_constraintHorizontal_bias="0.454"
199          app:layout_constraintStart_toStartOf="@+id/temp_sunday"
200          app:layout_constraintTop_toTopOf="@+id/temp_sunday"
201          app:layout_constraintVertical_bias="1.0" />
202  
203      <Button
204          android:id="@+id/btncalculate"
205          android:layout_width="wrap_content"
206          android:layout_height="wrap_content"
207          android:text="calculate"
208          tools:layout_editor_absoluteX="274dp"
209          tools:layout_editor_absoluteY="634dp" />
210  
211  </androidx.constraintlayout.widget.ConstraintLayout>



the purpose of this aplication is to serve as a convience when people want to check weather forecasts in their country/cities. the weather app that can calculate the weekly average temperature is an extraodinarytool for people to plan their daily activities and make informed decisions  the main purpose of this app is to provide users with accurate and up to date weather information,including the average temperature for a set week.

knowing the weekly average assits in everyday lives such as outdoor events, trips, or sports games. So if a user is able to calculate the average temperature users are able to repare their week accordily etc: dreesing up

Extreme temperatures can be dangerius to human health a weather app with daily and weekly average temperatures helps users to not over dress themselves in the heat and underdress themselves in the chilly weather.

tourists rely on weather apps to plan their visits and vacation. Such an app can be useful to inform users what to pack in their luggage and make informed decisions about their destination.

this weather app can also help businesses optimise energy consumpution by knowing the temperature the can adjust their cooling and heating systems to reduce costs.

farmers may also rely on the weather for harvesting and crop management bto avoid things such as over watering crops and understanding temperature trends

in conclusion a weather app that can calculate the weekly average temperature is an essential tool for various aspects to life ranging from personal planning and health to argiculture and climate change reasearch.By providing accurate  and reliable weather forecasts such an app helps users make informed descions


start

user opens app
user exits app or go to main screen

main screen



