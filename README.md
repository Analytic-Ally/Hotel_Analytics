# A Deep Dive into Hotel Analytics for Optimal Performance 🌱✨

Embark on a Data Odyssey: Elevating Hospitality with Python-Powered Hotel Analytics. This project seamlessly integrates cutting-edge Python libraries to analyze user-generated queries and input data, crafting a sophisticated narrative of hotel performance. Through the lens of predictive modeling, delve into future projections, unraveling the insights that guide strategic decisions for an unparalleled guest experience and operational excellence.


<img align="right" alt="Coding" width="400"  src="https://img.freepik.com/premium-photo/anime-girl-with-headphones-laptop-generative-ai_170984-11186.jpg">



# Languages and Tools 📇 :- 

 <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://docs.anaconda.com/_static/Anaconda_Icon.png"/>
<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg/2203px-Microsoft_Office_Excel_%282019%E2%80%93present%29.svg.png"/>
<img align="left" alt="Spring" width="30px" style="padding-right:10px;" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQlHRnipUXQrWtvaTcEETmEOyL9ecApYEpHlCx3e3ASHkF8_c9dg3TzQrbli2N3536crs&usqp=CAU" />
<img align="left" alt="Angular" width="30px" style="padding-right:10px;"
src="https://w7.pngwing.com/pngs/170/924/png-transparent-microsoft-sql-server-microsoft-azure-sql-database-microsoft-text-logo-microsoft-azure.png" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/883px-Jupyter_logo.svg.png" />

# Badges 💖


![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tushar-gupta-3b29b5144//)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/TusharG8127)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

# Insights Generation 🌟🍀


```
1. df_agg_bookings.head()

```
![Screenshot 2023-12-11 152844](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/4d904d0d-e64b-4d1f-9696-44a2f59f89da)

``` 
2. df_agg_bookings.groupby('room_category')['occ_pct'].mean()
```
![Screenshot 2023-12-11 152909](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/b69c95b6-3fe8-48f7-9dec-02cf1961d3d8)

```
3. df_rooms.head()
```
![Screenshot 2023-12-11 152917](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/7806fd3a-4d05-46d5-b1ae-19429f8c5835)

``` 
4. df = pd.merge(df_agg_bookings,df_rooms,left_on='room_category',right_on='room_id')
df.head()
```
![Screenshot 2023-12-11 152928](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/92972b85-4531-4e57-a63a-4d220875b7b2)

``` 
5. df.groupby('room_class')['occ_pct'].mean().plot(kind='bar')
```
![Screenshot 2023-12-11 152947](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/fbfdf48e-f104-400f-a43a-15b043422bb8)

```
6. df.groupby('day_type')['occ_pct'].mean().round(2).plot(kind='pie')
```
![Screenshot 2023-12-11 153019](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/1497fad4-4a9d-4dd8-b610-a0e2e04e696d)

``` 
7. df_updated_bookings.groupby('booking_platform')['revenue_realized'].sum().sort_values(ascending=False).plot(kind='pie')

```

![Screenshot 2023-12-11 153042](https://github.com/Analytic-Ally/Hotel_Analytics/assets/149322654/ef7c9b13-b1c5-4e1c-bc1e-586d2f8ea4e5)

---

# Connect With Me 📝 :- 

  <div align="center">
<img src="https://i.imgur.com/KXx0cCx.gif" align="right" width="373.5px" height="208.5px">
  </div>
<br>
<p align="center"> Looking Forward <br>
 to sharing this journey with you! Excited </p>
  
<p align="center">
<a align= "centre" href="https://twitter.com/tusharg41" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="tusharg41" height="30" width="40" /></a>
<a href="https://linkedin.com/in/tushar-gupta-3b29b5144/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/tushar-gupta-3b29b5144/" height="30" width="40" /></a>
<a href="https://instagram.com/tushargupta_8127/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.instagram.com/tushargupta_8127/" height="30" width="40" /></a>
<a align= "centre" href="https://www.hackerrank.com/profile/tanugupta3367" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="https://www.hackerrank.com/profile/tanugupta3367" height="30" width="40" /></a>
</p>

<h3 align="center">For support, email <a href="/">tanugupta3367@gmail.com</a> or join throught linkedin .</h3>




