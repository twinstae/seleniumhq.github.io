---
title: "셀레니움 프로젝트와 도구들"
weight: 1
---


### 셀레니움은 웹 브라우저를 조종합니다.

셀레니움은 하나가 아니라 여럿입니다.
하지만 그 핵심은 웹브라우저 자동화를 위한 도구 모음이라는 겁니다. 셀레니움은 원격으로 브라우저의 인스턴스들을 조종하고, 브라우저와 사용자의 상호작용을 모방하는데 가용한 최고의 기술을 사용합니다.

셀레니움을 쓰면 실제 사용자가 할 법한 행동들을 모의할 수 있게 됩니다;
필드에 텍스트 입력하기
드롭 다운 값이나 체크 박스 선택
문서에 링크 클릭하기
그 외에도 마우스 움직임이나, 임의의 자바스크립트 실행, 그 이상을 제공합니다.

비록 웹사이트의 프런트엔드 테스트에 주로 사용하긴 하지만, 셀레니움은 그 핵심인 브라우저 사용 행위자(user agent) _library_ 에 있습니다.
이 인터페이스는 어플리케이션 어디에나 응용할 수 있고, 용도에 맞는 다른 라이브러리와 함께 구축하는 것도 장려합니다.

### One interface to rule them all

One of the project's guiding principles
is to support a common interface for all (major) browser technologies.
Web browsers are incredibly complex, highly engineered applications,
performing their operations in completely different ways
but which frequently look the same while doing so.
Even though the text is rendered in the same fonts,
the images are displayed in the same place
and the links take you to the same destination.
What is happening underneath is as different as night and day.
Selenium “abstracts” these differences,
hiding their details and intricacies from the person writing the code.
This allows you to write several lines of code to perform a complicated workflow,
but these same lines will execute on Firefox,
Internet Explorer, Chrome, and all other supported browsers.


### Tools and support

Selenium's minimalist design approach gives it the 
versatility to be included as a component in bigger applications.
The surrounding infrastructure provided under the Selenium umbrella
gives you the tools to put together
your [grid of browsers]({{< ref "/grid/_index.md" >}})
so tests can be run on different browsers and multiple operating systems
across a range of machines.

Imagine a bank of computers in your server room or data center
all firing up browsers at the same time
hitting your site's links, forms,
and tables&mdash;testing your application 24 hours a day.
Through the simple programming interface
provided for the most common languages,
these tests will run tirelessly in parallel,
reporting back to you when errors occur.

It is an aim to help make this a reality for you,
by providing users with tools and documentation to not only control browsers,
but to make it easy to scale and deploy such grids.


### Who uses Selenium

Many of the most important companies in the world
have adopted Selenium for their browser-based testing,
often replacing years-long efforts involving other proprietary tools.
As it has grown in popularity, so have its requirements and challenges multiplied.

As the web becomes more complicated
and new technologies are added to websites,
it's the mission of this project to keep up with them where possible.
Being an open source project,
this support is provided through the generous donation of time from many volunteers,
every one of which has a “day job”.

Another mission of the project is to encourage
more volunteers to partake in this effort,
and build a strong community
so that the project can continue to keep up with emerging technologies
and remain a dominant platform for functional test automation.


### History

When Selenium 1 was released in 2004,
it was out of the necessity to reduce time spent
manually verifying consistent behaviour in the front-end of a web application.
It made use of what tools were available at the time 
and relied heavily on the injection of JavaScript to the web page under test
to emulate a user's interaction.

Whilst JavaScript is a good tool to let you introspect the properties of the DOM
and to do certain client-side observations that you would otherwise not be able to do,
it falls short on the ability to naturally replicate a user's interactions
as if the mouse and keyboard are being used.

Since then, Selenium has grown and matured a lot,
into a tool widely used by many&mdash;if not most&mdash;of
the largest organisations around the world.
Selenium has gone from a homebrewed test automation toolkit developed at Thoughtworks
for a niché audience and a specific use case,
to the world's _de facto_ browser automation library.

Just as Selenium RC made use of the tools of the trade available at the time,
[Selenium WebDriver]({{< ref "/webdriver/_index.md" >}}) drives that tradition on by taking
the browser interaction part to the browser vendor's home turf 
and asking them to take responsibility of the backend, browser-facing implementations.
Recently this work has evolved into a W3C standardisation process
where the goal is to turn the WebDriver component in Selenium
into the _du jour_ remote control library for user agents.
