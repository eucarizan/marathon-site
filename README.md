# site for marathon

- [site for marathon](#site-for-marathon)
  - [learning](#learning)
  - [about](#about)
  - [stages](#stages)
    - [1: embed iframes](#1-embed-iframes)
    - [2: style iframes with css](#2-style-iframes-with-css)
    - [3: add disances and descriptions](#3-add-distances-and-descriptions)

## learning
focus on htmls andc css: basic styles and positioning. use iframes to embed external content to your webpage. work with images and add animation.

## about
you were hired by an ngo to build a site for one of the marathons in london. there are certain requirements, the site must show distances, weather, and the map of the marathon. sound interesting? let's dive into it!

## stages
### 1: embed iframes
<details>
<summary>use iframes to add external content to a web page. start by adding a youtube video and a weather forcast to you page.</summary>

#### 1.1 description
let's start creating the landing page by adding two `iframes` to the page.

the first `iframe` should contain a motivational video for runners from youtube. you can choose any video that inspires and motivates runners to participate in the race.

the second `iframe` will display the london weather forecast. use the weather widget from [meteoblue](https://www.meteoblue.com/en/weather/widget/setupday). please configure the widget to display the weather of london for 7 days, including the icon, minimum and maximum temperature, wind speed and direction.

wrap each iframe in a block with an `iframe-container` class to further work with the styles.

#### 1.2 objectives
at the first stage, you should have:
- `iframe` with an embedded youtube video;
- `iframe` with a weather widget;
- each `iframe` must be wrapped in a block with a class `iframe-container`

#### 1.3 examples

![stage 1 marathon site design](./s01.png)

</details>

### 2: style iframes with css
<details>
<summary>style the iframes in the previous stage with css, including positioning and sizing them to fit perfectly on your web page.</summary>

#### 2.1 description
in the previous stage, you added youtube and weather `iframes` to the landing page. now, change the style of these `iframes` using css so that they could fit the page perfectly.

position the `iframe-container` so that they follow each other and take up 100% of the screen width without `margins` or `padding`.

>at this stage, using relative units like `vw` for the `iframe-container` should help!

also, adjust the height of the youtube `iframe` and weather `iframe` to be 80% and 40% of the available screen height respectively while keeping the width of both frames. this will help users understand that our branding is not limited to just the video. you can use the `overflow` and `position` properties in your css code to position the elements.

finally, let's remove unnecessary controllers from the youtube `iframe`. `controls=0` will help you. 

#### 2.2 objectives
- set the width of both iframe-container to 100% of the screen width;
- set the height of the youtube `iframe` to 80% of the screen height and the height of the weather `iframe` to 40% of the screen height;
- remove any `margin` and `padding` from the `body` and `iframes`;
- hide the controls for youtube `iframe`.

>make sure to remove the already present inline css from the weather iframe.

#### 2.3 examples

![stage 2 site for marathon design](./s02.png)

</details>

### 3: add distances and descriptions
<details>
<summary>add descriptions of distances and images to the project</summary>

#### 3.1 description
previously, you added youtube and weather `iframes` to the landing page and styled them using css. now it's time to add a list of distances along with their descriptions and images.

create a new block with the `` class below the iframes. inside this block, add a header (`h2`) with the text `running distances` and an unordered list (`ul`) with five list items (`li`) with the `distance` class. each list item should contain an image, a title, and a description of the distance.

>you can write content inside the lists section as per your choice. below given content is used in the example image.

here are the details for each distance:
- 1km, title `1km run`, the image is any fun running image, description: `this short and sweet 1km run is perfect for beginners or those who just want to have a bit of fun. whether you're looking to kickstart your fitness journey or simply enjoy a leisurely jog in the great outdoors, this distance is a great way to get started.`
- 5km, title `5km run`, the image is any image related to a 5 km race, description: `with a distance of 5km, this run is a great challenge for beginner runners or those who want to improve their fitness. whether you're looking to increase your speed or endurance, this distance will test your limits and help you reach your goals.`
- 10km, title `10km run`, the image is any image related to a 10 km race, description: `the 10km run is a great intermediate distance that offers a challenge to runners who have already tackled shorter races. with a mix of speed and endurance, this distance requires a bit more training and dedication, but the sense of accomplishment you'll feel at the finish line will be well worth it.`
- 21km, title `half marathon`, the image is any image related to a half marathon, description: `the half marathon is a major milestone for runners and requires dedicated training to complete. at a distance of 21km, this run will push you to your limits both physically and mentally, but the feeling of crossing the finish line is an experience like no other.`
- 42km, title `full marathon`, the image is any image related to a full marathon, description: `the full marathon is the ultimate challenge for runners and requires months of intense training to complete. with a distance of 42km, this run is not for the faint of heart, but for those who are willing to put in the time and effort, the feeling of crossing the finish line is a truly unforgettable experience.`

#### 3.2 objectives
1. create a block with class distance-container below iframes and add a h2 header with the text "running distances".
2. create an unordered list with five list items with the distance class inside the distance-container block.
3. put an image, title, and description for each distance.

#### 3.3 examples

![stage 3 site for marathon design](./s03.png)

</details>

[<<](https://github.com/eucarizan/front-end/blob/main/README.md)
<!--
:%s/\(Sample \(Input\|Output\) \d:\)\n\(.*\)/```\r\r**\1**\r```\3/gc

### 0: 
<details>
<summary></summary>

#### 0.1 description

#### 0.2 objectives

#### 0.3 examples

</details>
-->

