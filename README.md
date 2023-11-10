[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/bwEfZG3u)

>**!Note**
> This is repository for assignment on checkpoint #2 "deployment of project from Week 1-3"
> detail about the website project you can check on my other repository here : [Web-project](https://github.com/Blackpossum/module-1-yosephat-assigment)
# Deploying a static Websites
##### this is a guide to help you deploy your static websites from your repository using netlify to host your project,please follow along this steps as a tutorial guide:

> [!IMPORTANT]
> prerequisite : have a static website ready for deployment 
> have a basic knowledge about git repository management.
> have a netlify account or willing to register to Netlify.
> provide custom domain name, or you can either use free domain from netlify. 

## deploy repository to a third party hosting
1. first things first, in this tutorial guide we will use for hosting our project repository, open netlify site here i'll provide you a link (https://app.netlify.com/) and Login into your Netlify account (if you dont have account on netlify,you can choose signup button to register your account on netlify).

![Landing-page](/assets/mrkdwn-assets/netlify-landing.png).
![login](/assets/mrkdwn-assets/login-netlify.png)

on login option page use your preffered platform that you use for your project repo, in this case we will use github account for login to Netlify.

![login-page](/assets/mrkdwn-assets/login-page.png)

2. after login completed, you'll redirected to your repository page on netlify 
and wil be ask to choose repository to be hosted, choose your project repo and click deploy.

![repo-management](/assets/mrkdwn-assets/netlify-repo-list.png)

3. next you will be redirected into your site page
![netlify-dashboard](/assets/mrkdwn-assets/netlify-site%20overview.png)

if you just deploy, it might need few minute untill your deploment can be accesed, when the proccess completed, the link to your site will be in blueish color like image above.

4. for now your project is already can be accesed via netlify default domain.

## setting and Establishing custom domain and register it into Netlify

### buy a domain on Niagahoster
in order to register custom domain on netlify, you need to have a custom domain first
go to domain hosting provider to buy a custom domain, in this tutorial guide i will use __Niagahoster__ as my domain registrar for my costume domain.

1. go to Niagahoster site, and buy a domain name for your site here i provide you the link 
go to (https://www.niagahoster.co.id/domain-murah)

2. you will be redirected to niaga hoster page, type your domain name and cek for availability of the domain, is it already taken or not
![domain-search](/assets/mrkdwn-assets/niaga%20hoster%20page.png)

3. if your domain is available to use, purchase the domain name and after payment completed you will be redirected to your domain management in Niagahoster 
![availability](/assets/mrkdwn-assets/availability%20.png)

4. open your domain management page, you will found your domain DNS and another configuration, leave it for now.
![niagahoster](/assets/mrkdwn-assets/niagahoster.png) 
![domain-info](/assets/mrkdwn-assets/domain%20information%20.png) ![DNS-server](/assets/mrkdwn-assets/hostinger-dns.png)

### register custom domain on Netlify

1. go to your netlify site-overview page > go to yoaur site cnfiguraton 
![site-config](/assets/mrkdwn-assets/site-configuration.png)

2. go to domain tab on the left panel > then click add custom domain > enter your custom domain
![enter-domain](/assets/mrkdwn-assets/netlify-add-domain.png) then click add domain 

3. create a CNAME record on Niaga hoster that point to your default netlify domain 
![DNS](/assets/mrkdwn-assets/rococo.png)

4. it will take a while for your custom domain is recognize by netlify, if the proccess is completed , the warning of awaiting external DNS change to netlify DNS (if you using netlify DNS server, if you using your external provider theres no warning appears)
![domain-management](/assets/mrkdwn-assets/domain%20management.png)

5. back to netlify tab,after your domain is active , netlify also provide TLS encryption for your domain an sub domain, these encryption is use for secure site request , in other words convert HTTP to HTTPS 
you can check by scrolling down the page 

![TLS](/assets/mrkdwn-assets/netlify-TLS-verify.png)
if yor dns not verify you can click `retry DNS verification`

if the verification completed, you should se the section content change to this 
![verify](/assets/mrkdwn-assets/nelify-TLS-cert.png)

### and now yaour site already deployed and can be visited by yaour costume domain.\
@buy_me_a_coffe blackpossum 2023


## My Bio :pencil2:

hi!, my name is prasta, im a Mechanical engineer.

<img src="assets/WhatsApp%20Image%202023-10-10%20at%2016.24.56.jpeg" width=40%> 

Iam an expirienced for almost 3 years as `Mechanical Engineer`, my main focus is on sparepart replacement and mechanical configuration. i currently working in paper and forestry industry, and now , im starting a new journey to Learn about `software Engineering` field in __RevoU__ bootcamp Academy.

* __how i end up here__ :
starting from expiriencing working project with overseas vendor,
installing a new software integrated machine, i was blown away with the complexity of the installation.
from there i start noticing engineering in different prespective, that machine in near future cannot operate just by transfering energy from one motion to become another motion anymore<br>
`the future` is about how to build an integrated system that can works with machine part dynamicaly to increase output rate, seeing this if i only look and dont improve i will be left behind technology, thats why im here.

## My links :rocket:
* __find me On :__ 

|Platform |  Links       |
|------------|---------|
__linkedin__![linkedin](assets/icons8-linkedin-30.png)| [yosephat Harwindra](https://www.linkedin.com/in/yosaphat-harwindra-82aa54194/)|
|__github__ ![github](assets/icons8-github-30.png)|[blackpossum](https://github.com/Blackpossum)
|__mail me__![gmail](assets/icons8-gmail-30.png)| [yosaphatharwindra@gmail.com](yosaphatharwindra@gmail.com)|


## My Technical programming skill :wrench:
 * self-taught skill:
    - `Markdown`
    - `HTML`
    - basic `CSS`
    - `javascript`
    - `node.js`
    - `Terminal & CLI`
    - `git & github`
 * another skill :
  - __Dev-Ops :__ CALMS framework 
  - __AWS EC2 & VPC__ - AWS training
  - __Computer Networking__ - _by google_
  you can check the certificate on my [Linkedin account](https://www.linkedin.com/in/yosaphat-harwindra-82aa54194/details/certifications/)

## My favorite sites :globe_with_meridians:
| platform | links | usage |
|----------|-------|-------|
| google   |https://www.google.com | __for serching resources__ |
| microsoft learn |https://learn.microsoft.com|__for Learning Material__|
| MDN  & ChatGPT| https://www.developer.mozila.com|__problem & Solution__|
||https://chat.openai.com/|__problem & Solution__|
|codewars|https://www.codewars.com|__exercise with code & algorithm__|
| music |https://www.spotify.com|__refreshing__|
|coolors|https://coolors.co|__coolors palette__|
    


## My code Sniplet :books:

__markdown__
```markdown
    ## this is a heading 
        1. this is  ordered list `embed text`
            - unorder list 
```

__HTML__
```HTML
    <h1>this is a heading</h1> 
       <ul> 1. this is  ordered list `embed text`
             <li>unorder list </li>
       </ul> 
```

__CSS__
```css
     h1 {
        background-color:#052538;
        height:60px;
        width:50px;
        display: flex;
        align-self:center;
     }
```
__JS__
```js
    const greetings = (name) => {
        console.log(`Hi welcome ${name}`)
    };
```
__git__
``` 
  git status
    git add
    git commit
```

# Website project
hi!, there is an update, im working on a new static web project 
if you want to see, i provide you the link netlify app :https://rococo-pavlova-af74e4.netlify.app/
check it, if you have a suggestion you can connect with me in my github account [blackpossum](https://github.com/Blackpossum)<br>

## what's the website about?
it's about koala activist, basicaly its a landing page for join a koala activist comunity, i inspire by the weather these days that insanely hot,<br>
im starting to missing rain :cloud_with_rain: so i been thinking about what animal live in a drought hot place and surviving it, and viola....koala :koala:<br>
_yosephat harwindra@10/2023_