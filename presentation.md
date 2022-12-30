# Tunisia baccalaureate data analysis 2010 - 2022
**`Written and edited by: Skander Boudawara - 27/06/2022`**

Do not hesitate to contact me through my LinkedIn Profile
<p>
<a href="https://www.linkedin.com/in/skanderboudawara/">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a> 
<br>
</p>

_ _ _


## Context:
**24 June 2022** is the results day of the most awaited exam, "The Tunisian baccalaureate." The "Bac" is considered one of the most crucial steps to finishing high school and starting the university curriculum. I wanted to focus on the data presented over the last ten years and try to have some conclusion and why not confirm or deny my personal bias. ( this study is for personal fun and not intended for other use) 

At first, I thought it would be a piece of cake, and as Tunisia proclaims under the project "Digital Tunisia," I would easily find the data, and in one run, I will have my visualizations. However, these are the issues I encountered:
- The data are not available on the official government website.
- Some data are available on the Facebook page of the Ministry of Education but not always in the same format. 
- Some data are available on local newspapers and radio and are painful to find & parse (Yeah, sometimes I listened to an entire archived radio cast to extract one or two values)


I decided then to manually fill the data needed for my analysis through Google Sheets ( Spreadsheet link ) and try my best to avoid any mistype (even though the risk is still high).

<u><b>The scope of my analysis:</b></u>
- Period: from 2010 - 2022
- High School: Public & Private
- Number of registered pupils for the exam (Public & Private)
- Success rate, gender partition
- Region ranking by success rate
- High Marks, gender partition & their high school of origin

It took me about 4 hours to find and parse the data needed. So yeah, let's finally start our analysis.

_ _ _ 

# I - Pupil registered for the BAC exam
## 1- Repartition over the years

<img alt="Total number of pupils registered for the baccalaureate examination per year" src="src/Total number of pupils registered for the baccalaureate examination per year.svg">

We do not have a significant variation in the number of the total registered pupils throughout the year. In fact, between the min & max is a leap of 20k pupils, which is not significant.

## 2- Distribution of pupils registered per field 

<img alt="Distribution of pupil registered per field" src="src/Distribution of pupil registered per field.svg">

From this graph, we can see that:

- On the one hand, there is a craze for the technical field and the economics and management field
- On the other hand, a lack of interest in the mathematics and computer science field (which is odd in the digital and computer science area)
To be honest with you, since I was a student in the mathematical field (BAC 2011), I am a bit astonished. I always thought that Math was the first target of Tunisian students for the opportunities it may offer. It seems that is not a general trend and pupils are more and more choosing between Economics & management or Technical field. I don't know the real reason behind this trend.
- Is it a strategic decision made by the government?
- Are these two fields easier than the other?
- Do these fields offer more Job opportunities in the local market?
Now let's go back and analyze the success rate.

## 3- Sucess, adjournment & refusal rate distribution

<img alt="The success, adjournment, and refusal rate distribution over the total registrations" src="src/The success, adjournment, and refusal rate distribution over the total registrations.svg">

At first glance, the refusal rate seems to increase through the year; meanwhile, the success rate is decreasing, and the adjournment rate is stable. We will check later on the evolution of each rate.

Let's look closely at the performance (variation) of the success rate over the years.

<img alt="Variation of the success rate compared to the previous year" src="src/Variation of the success rate compared to the previous year.svg">


- 2012 & 2015 are the worst year in success rate performance when they dropped by 26%
- 2021 is the best year in success rate performance (knowing that this year was highly impacted by Covid 19)

Now let's analyze the trend & performance of each year between 2010 - 2022

<img alt="Adjournment rate trend" src="src/Adjournment rate trend.svg">  <img alt="Refusal rate trend" src="src/Refusal rate trend.svg">  <img alt="Success rate trend" src="src/Success rate trend.svg">

As far as I'm concerned, I find these three graphs really alarming!
The success and adjournment rate (all fields included) is decreasing, and on the contrary, the refusal rate is increasing significantly with a strong positive slope.
- Is it due to a deterioration in our educational system?
- Is our educational system no more suitable for the current generation?
- Are the recurrent "catastrophic events" that led to separate cut-period such as student strikes, gouv strikes, teacher strikes, "Covid 19", "Jasmin Revolution", etc ... responsible for this downgrade?

On top, what are the strategic and the real actions that are taken to overcome this issue?

<img alt="Evolution of success rate between 2010 & 2020 distributed by fields" src="src/Evolution of success rate between 2010 & 2020 distributed by fields.svg">

## 4- Average success rate by gender

No surprise here, the average success rate is crowned by the female gender with a crushing percentage of 63.5% over 36.5% for males.

I invite you to have a look at the analysis made by InkyFada about this topic.

Link to the [article](https://inkyfada.com/fr/2021/09/10/inegalites-hommes-femmes-ecole-travail-tunisie/)

<img alt="Average distribution of success rates between different sexes" src="src/Average distribution of success rates between different sexes.svg">

_ _ _

# II- Laureate & High marks analysis

It's always a pleasure to read and learn more about the laureate of each field and the high mark they got during this challenging exam. Back in the day, I always aimed to dethrone my predecessor and get a new achievement. But unfortunately, even though I got a good grade (17,80), It was not sufficient to be on the podium in 2011.

Let's see the evolution of high marks over the years and what is the field that has achieved it.

## 1 - Evolution of high marks over the years

<img alt="Highest baccalaureate mark per year" src="src/Highest baccalaureate mark per year.svg">

As we can see, the highest mark is always coming from the Mathematical or Experimental science field, which is quite understandable. Those fields are based on true/false types of exams. Either you are correct, or either you are wrong. Meanwhile, the other areas need some work and subjective marking.
We can see also that the trend of High marks has a positive slope but who will beat the best among the bests 20,15/20? The bug in the system? the Neo of the Matrix.?

We will consider one laureate of each field:
- Literature
- Mathematics Sc
- Experimental Sc
- Economics and Management
- Sport
- Computer Sc
- Technical Sc

and we will deep dive into their school of origins, their gender, and so on.

## 2- Gender distribution between laureate

<img alt="Distribution of laureat by gender" src="src/Distribution of laureat by gender.svg">

Unlike the average total gender distribution, the gender distribution in the laureate is competitive and somehow equal between males & females. (except for 2010, a major win for females)

## 3- High school of origin of the laureate (Pilote vs Other schools)

<img alt="Distribution of the laureate on the high schools" src="src/Distribution of the laureate on the high schools.svg">

Astonishingly the repartition of laureates between public high schools and "pilot" high schools is equal. The pilot high school is slightly better, but not with a significant leap. For instance, pilot high schools were established to offer the toughest and the best education in the region for the laureate of each region.

## 4- The high school with the most laureate number

[^1] HS stands for High School

<img alt="Total of laureate distributed per High School" src="src/Total of laureate distributed per High School.svg">

But as we can see, High School Pilote Sousse is the school that has created more laureates in the country over the last decade. The top field for this school is Technique, with eight laureates between 2010 - 2022. Finally, let's have a look at their region of origin

## 5- Region of the High school of the laureate

<img alt="Distribution of laureate by region, cumulative view" src="src/Distribution of laureate by region, cumulative view.svg">

I expected Sfax or Sousse to be at the head of this Pareto, but surprisingly it's Tunis (downtown) with 23 laureates that win the podium, followed by Sousse then Sfax.

Speaking of the region, let's look at the success rate distributed by region.

_ _ _

# III- Success rate per region

To create these charts, I used the library high-charts combined with Google script (The source code as below)

<details>
<summary>Code</summary>

    var Route = {}
    Route.path = function (route_x, callback){
    Route[route_x] = callback;
    }
    function doGet(e) {
    Route.path('2015page',load2015)
    Route.path('2018page',load2018)
    Route.path('2022page',load2022)

    if (Route[e.parameter.v]){
        return Route[e.parameters.v]()
    }
    else {
        return render('2015page')
    }
    }

    function load2015() {
    return render('2015page')
    }

    function load2018() {
    return render('2018page')
    }
    function load2022() {
    return render('2022page')
    }



    function include(filename) {
    return HtmlService.createHtmlOutputFromFile(filename).getContent()
    }

    function render(file, argsObject){
    var tmp = HtmlService.createTemplateFromFile(file)
    if (argsObject){
    var keys = Object.keys(argsObject)
    keys.forEach(function(key) {
        tmp[key] = argsObject[key]
    })
    }
    return tmp
    .evaluate()
    .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)
    .setTitle('tunisia_map_bac')
    }

</details>

<details>
<br>
<summary> page.html </summary>

    <!DOCTYPE html>
    <html>
    <head>
    <base target="_top">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
    </head>
    <body>
    <div id="container" class="container"></div>


    </body>
    <script src="https://code.highcharts.com/maps/highmaps.js"></script>
    <script src="https://code.highcharts.com/maps/modules/exporting.js"></script>
    <script src="https://code.highcharts.com/maps/modules/offline-exporting.js"></script>
    <script src="https://code.highcharts.com/maps/modules/accessibility.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js" integrity="sha384-Xe+8cL9oJa6tN/veChSP7q+mnSPaj5Bcu9mPX5F5xIGE0DVittaqT5lorf0EI7Vk" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.min.js" integrity="sha384-kjU+l4N0Yf4ZOJErLsIcvOU2qSb74wXpOhqTvwVx3OElZRweTnQ6d31fXEoRD1Jy" crossorigin="anonymous"></script>
    <script>
    // Prepare random data
    var data = [ [ 'AR' , 37.39 ]  , [ 'BA' , 29.5 ]  , [ 'BJ' , 20.06 ]  , [ 'BZ' , 28.75 ]  , [ 'GB' , 24.04 ]  , [ 'GF' , 14.83 ]  , [ 'JE' , 15.4 ]  , [ 'KB' , 18.76 ]  , [ 'KF' , 21.1 ]  , [ 'KR' , 17.94 ]  , [ 'KS' , 11.41 ]  , [ 'ME' , 35.56 ]  , [ 'MH' , 36.54 ]  , [ 'MN' , 24.23 ]  , [ 'MS' , 36.51 ]  , [ 'NB' , 31.18 ]  , [ 'SF' , 43.545 ]  , [ 'SL' , 23.31 ]  , [ 'SS' , 36.28 ]  , [ 'SZ' , 16.68 ]  , [ 'TA' , 18.29 ]  , [ 'TO' , 19.58 ]  , [ 'TU' , 28.055 ]  , [ 'ZA' , 23.25 ]  ] ;

    Highcharts.getJSON('https://code.highcharts.com/mapdata/countries/tn/tn-all.geo.json', function (geojson) {

    // Initialize the chart
    Highcharts.mapChart('container', {
        chart: {
            map: geojson
        },

        title: {
            text: 'Success rate per region 2015'
        },

        accessibility: {
            typeDescription: 'Map of Tunisia.'
        },

        mapNavigation: {
            enabled: false,
            enableButtons: false
        },

        xAxis: {
            
            labels: {
                enabled: true
            }
        },


        colorAxis: {
            labels: {
                format: '{value}%'
            },
            showEmpty: true,
            enabled: false,
            tickPixelInterval: 50
        },

        series: [{
            data: data,
            keys: ['postal-code', 'value'],
            joinBy: 'postal-code',
            name: 'Sucess rate',
            states: {
                hover: {
                    color: '#a4edba'
                }
            },
            dataLabels: {
                enabled: false,
                format: '{point.properties.postal-code}'
            }
        }]
    });
    });
    </script>
    </html>
</details>
<br>
<img alt="tunisia heat map" src="src/tunisia heat map.jpg">
<br>

As we can see here, the coastal areas have a better success rate than the inner region. This trend didn't change over the last decade, a critical issue due to the inner region's lack of investment (cultural & economical). You can check Inkfyada as well for better documentation.

_ _ _

# Conclusions
- This study has helped a better concrete view of the actual situation for the baccalaureate data.
- It has corrected some biases, especially for the mathematical fields and the pilote school trend.
- This study has some alarming indicators, such as the increase in refusal rate & the success rate distribution per region.
- I tried to use simple visualization, which, to be honest, was quite challenging trying to find the balance between "remove the clutter" and "over-simplification."
- Unfortunately, much data for Tunisia is inaccessible or unavailable, or their recreation is challenging! I hope one day our data become publically available so we can do our investigation.
  

<u><b>Critics:</b></u>
- These data must be crossed with other data to be able to make more concrete and objective decisions.
- The data that are in the Google spreadsheet are manual data without a double-check from an external, so some minor errors can be made

_ _ _

Do not hesitate to contact me through my LinkedIn Profile
<p>
<a href="https://www.linkedin.com/in/skanderboudawara/">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a> 
<br>
</p>