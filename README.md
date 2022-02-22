<link rel="canonical" href="https://levelup.gitconnected.com/observer-design-pattern-in-net-c-55633462f18e?sk=1362e513c0a814acfadca68af9596d3b" />

# Observer Design Pattern in .NET C#
### Learn about the Observer Design Pattern in .NET C# with some enhancements.

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*3hR3XW3r2YaVJdGRPF4jcw.jpeg">
</p>

<br/>

<p>
The Observer Design Pattern is one of the most important and commonly used design patterns, and this is for a reason.
</p>

<br/>

<p>
First, let’s check the formal definition of the Observer Design Pattern.
</p>

<br/>

<p>
As per Microsoft’s documentation: The observer design pattern enables a subscriber to register with and receive notifications from a provider. It is suitable for any scenario that requires push-based notification. The pattern defines a provider (also known as a subject or an observable) and zero, one, or more observers. Observers register with the provider, and whenever a predefined condition, event, or state change occurs, the provider automatically notifies all observers by calling one of their methods. In this method call, the provider can also provide current state information to observers. In .NET, the observer design pattern is applied by implementing the generic System.IObservable<T> and System.IObserver<T> interfaces. The generic type parameter represents the type that provides notification information.
</p>

<br/>

<p>
So, from the definition above, we can understand the following:<br/>
1. We have two parties or modules.<br/>
2. The module which has some stream of information to provide. This module is called Provider (as it provides information), or Subject (as it subjects information to outside world), or Observable (as it could be observed by outside world).<br/>
3. The module which is interested into a stream of information coming from somewhere else. This module is called Observer (as it observes information).
</p>

<br/>

If you are interested into reading more about this topic, you can read [the rest of the article][Article]. 

<br/>

## If you want to support me:
▶ Subscribe to Medium using [my referral link][Membership]<br/>
▶ Subscribe to [Medium Newsletter][Subscribe]<br/>
▶ Subscribe to [LinkedIn Newsletter][Newsletter]<br/>
▶ Follow me on [Medium][Blog]<br/>
▶ Follow me on [Twitter][Twitter]<br/>
▶ Follow me on [LinkedIn][LinkedIn]

<br/>

## Authors:
* [Ahmed Tarek Hasan]


[Ahmed Tarek Hasan]: https://medium.com/@eng_ahmed.tarek
[Blog]: https://medium.com/@eng_ahmed.tarek
[Membership]: https://medium.com/@eng_ahmed.tarek/membership
[Subscribe]: https://medium.com/subscribe/@eng_ahmed.tarek
[Twitter]: https://twitter.com/AhmedTarekHasa1
[LinkedIn]: https://www.linkedin.com/in/atarekhasan/
[Friend Links]: https://www.linkedin.com/feed/update/urn:li:activity:6866082670108143616/
[Newsletter]: https://www.linkedin.com/newsletters/development-simply-put-6866647119655247872/
[Article]: https://levelup.gitconnected.com/observer-design-pattern-in-net-c-55633462f18e?sk=1362e513c0a814acfadca68af9596d3b
