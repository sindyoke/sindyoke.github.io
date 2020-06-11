---
layout: default
title: Sindyoke's Android portfolio
---

<h2>{{page.title}}</h2>

<h3>What is a mechanical engineer doing in Android development?</h3>
The reason and drive is the same: I wanted to employ my talent for logic, mathematics, and my need to create something pulpable, that I can touch, hold, show, and that people will use and be happy :) Programming is even better than mechanical engineering, because it gives me more freedom, it's faster, and intellectually more rewarding.

<h3>Android experience</h3>
<ul>
	<li>2014. - Casual learning</li>
	<li>2015. - Full-time learning Android (see <a href="#courses">Courses</a>)</li>
	<li>2016-now - Full-time Android Developer in Delta Holding (see <a href="#apps">List of my applications</a>)</li>
</ul>

<h3>Tehnologies I work in</h3>
<ul>
	<li><strong>Google</strong> - Android Studio, Java, Locations, Maps, Street View, Analytics, Auth, Room</li>

	<li><strong>Firebase</strong> - RealtimeDatabase, Crashlytics, Authentication, Analytics, Cloud Messaging</li>
	
	<li><strong>Square</strong> - Retrofit, OkHttp3, Picasso, LeakCanary</li>
	
	<li><strong>Other libraries</strong> - Connecting to third party APIs: Facebook SDK, Triposo API, GitHub</li>
</ul>

<a name="courses"></a>
<h3>Courses I finished (this is not the full list)</h3>
<ul>
	<li><strong>Android</strong> - Programming Mobile Applications for Android specialization (<a href="https://www.coursera.org/account/accomplishments/verify/4D6L7Z92PZ">1 UI</a>, <a href="https://www.coursera.org/account/accomplishments/verify/HQK9DS4AM5">2 UI</a>, <a href="https://www.coursera.org/account/accomplishments/verify/54V9WRCTQ6">3 Concurrency</a>, <a href="https://www.coursera.org/account/accomplishments/verify/FH8VR9GZJL">4 Communication</a>, <a href="https://www.coursera.org/account/accomplishments/verify/Z5E3MKTCRG">5 Spring</a>, <a href="https://www.coursera.org/account/accomplishments/verify/Q86TZVQR5W">6 Security</a>), <a href="https://www.coursera.org/account/accomplishments/verify/HT2SQRZE6SEA">Engineering Maintainable Android Apps</a>, <a href="https://www.coursera.org/account/accomplishments/verify/QDPDDM645QQV">Android App Components - Intents, Activities, and Broadcast Receivers</a>, <a href="http://www.linkedin.com/learning/effective-android-testing-for-mobile-developers">Effective Android Testing for Mobile Developers</a>, <a href="http://www.linkedin.com/learning/android-espresso-essential-training">Android Espresso Essential Training</a>, <a href="https://www.udemy.com/certificate/UC-JZINA7BS/">Android Architecture Masterclass</a>, <a href="https://classroom.udacity.com/courses/ud258">How to User a Content Provider</a>, <a href="https://classroom.udacity.com/courses/ud867">Gradle for Android and Java</a>, <a href="https://classroom.udacity.com/courses/ud825">Android Performance</a>, <a href="https://classroom.udacity.com/courses/ud849">UX Design for Mobile Developers</a>, </li>
	
	<li><strong>Java</strong> - <a href="https://www.coursera.org/account/accomplishments/verify/PPXAA2WR86P4">Object Oriented Programming in Java</a>, <a href="https://www.coursera.org/account/accomplishments/verify/CEK9LEASEFFW">Data structures: Measuring and Optimizing Performance</a>, <a href="https://www.coursera.org/account/accomplishments/verify/2PB8HR7JHL5H">Advanced Data Structures in Java</a>, </li>
	
	<li><strong>Google</strong> - <a href="https://classroom.udacity.com/courses/ud876-4">Add Google Maps to your Android App</a>, <a href="https://classroom.udacity.com/courses/ud876-1">Google Location Services on Android</a></li>

	<li><strong>Firebase</strong> - <a href="https://classroom.udacity.com/courses/ud009">Firebase Essentials for Android</a>, <a href="https://classroom.udacity.com/courses/ud0352">Firebase in a Weekend</a>, <a href="https://classroom.udacity.com/courses/ud354">Firebase Analytics: Android</a></li>
</ul>

<h3>Courses I am currently attending online</h3>
<ul>
	<li>
		<strong>Android testing</strong> - <a href="https://www.udemy.com/course/professional-android-unit-testing/">Android Unit Testing and Test Driven Development</a>
	</li>
	
	<li>
		<strong>Kotlin</strong> - <a href="https://www.coursera.org/learn/kotlin-for-java-developers">Kotlin for Java Developers</a>, <a href="https://caster.io/courses/kotlin-programming-language">The Kotlin Programming Language</a>
	</li>
	
	<li>
		<strong>DevOps</strong> - <a href="https://www.edx.org/course/introduction-to-devops-and-site-reliability-engineering">Introduction to Site Reliability Engineering and DevOps</a>
	</li>
</ul>

<a name="apps"></a>
<h3>List of my Android applications</h3>
This is the list of some Android projects I worked on. Some are for the company I work for, and the others are my private projects. I was the only developer on all, except BMW and Honda, where I inherited the code and published a few updates.

{% assign myapps = site.apps | sort: 'order' %}
{% for app in myapps %}
	{% assign appname = app.url | replace_first: '/apps/', '' | replace: '.md', '' %}
  <h4><a href="{{ '/_apps/' | append: appname }}">{{ app.title }} - {{ app.owner }}</a></h4>
  <p>{{ app.desc | markdownify }}</p>
{% endfor %}

<h3>Me at work - speed, communication, values, problem solving</h3>
<ul>
	<li><strong>Responsibility</strong> - I will think thoroughly <strong>before</strong> I accept the job. If I accept it, don't doubt that I'll be on it, with my full energy and attention, and there's no need to check up on me constantly - most likely it would even be counterproductive. If you need more communication, be free to send me a message from time to time and I'd be happy to update you, but please don't expect me to send regular reports, unless I have some questions or doubts.</li>

	<li><strong>Communication channels I am currently using:</strong>
		<ul>
			<li>for written communication - SMS, Signal, Slack, Discord, LinkedIn, Facebook Messenger, Twitter</li>
			<li>for video conferencing as well - Viber, Skype, Skype for business, Microsoft Teams, Google Zoom & Hangouts & Meet, Jitsi Meet</li>
		</ul>
		I like to be networked, both with colleagues and friends. But when I work, I prefer to isolate myself with only the necessary tools for business. I used to believe in multitasking, but now I know it's just a myth. We need to minimize distraction to be able to focus => we need focus to achieve flow => and flow makes us happy! :)
		<br/>For business communication, I prefer texting to audio/video. Here's why: connection can be lousy, and because my ears are sensitive (that explains some of my weird musical talents, like playing by ear) that can prevent me from giving my full attention to the topic. Sometimes we have to repeat ourselves, and lose focus. Also, both parties don't have any proof about what we talked about. That's why I prefer written word: email, chat, ticketing system - communication is clear and there is no doubt about what has been agreed upon.</li>
	
	<li><strong>Speed</strong> - Give me a clear deadline and I will finish before it, or let you know in time if that's not possible. Don't give me open ends, and expect it to be fast - Work expands to fill the time available for its completion. (Parkinson's law)</li>
	
	<li><strong>Values</strong> - According to <a href="https://www.viacharacter.org/topics/articles/what-are-your-signature-strengths">VIA Institute</a>, my strongest signature strengths are: love of learning, curiosity, creativity, honesty, judgment, perspective. That means that I will do my best to solve any problems that may arise during the creation of your app. I go to sleep with the task in mind, and I solve it the next day if not sooner.</li>
</ul>