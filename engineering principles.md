## Engineering Principles at TotallyMoney


---

### We Own It

Ownership is the product of Autonomy, because if you have the freedom to choose you also are more likely to believe in your choices. It recognises the fact that we are a tech company, and we own the product. We own the problem space and should know what problem we are trying to solve for the customer extremely well.

#### Practices

- Know the customer
- Challenge yourself
- No deadlines
- Measure your success
- Everyone has a voice and can make a contribution
- #no-estimates
- Be a part of the product

#### Benefits:

- We go at our own pace
- No need to cut corners to make deadlines which please our clients
- We have control over the quality of the product
- You unlikely to get blocked for hierarchical reasons
- If you want to you can lead

#### Antipatterns:

- We can ignore the customer
- We don't need to be aligned with other parts of the company

---

### Move Fast and Deliver Value

Set yourself up to be able to deliver the most value for the customer with the least amount of friction. It’s about releasing often and without fear, knowing you can always fix any issue or roll back.

#### Practices

- Release often
- Enable speed through process
- Quality is a long term enabler
- Don’t chase perfection
- There’s nothing simple about simplicity
- Prioritise the problems that nobody has solved
- Be aware of services and libraries that can do the heavy lifting
- Focus on code that enhances the customer experience
- Use metrics or AB testing to confirm your hypothesis

#### Benefits

- Knowing it’s ok to release on Fridays
- Focussing on interesting problems not boilerplate
- Providing value to the customer

#### Anti-patterns

- Cutting corners to get stuff done
- Imagining what the customer wants without testing your hypothesis

---

### Openness & collaboration

Create an environment where time is spent on achieving tangible, beneficial outcomes. Be solution oriented. Do not be afraid to show what you don't know. Maximise learning - from failure, from success, from others.

#### Practices
- No blame culture
- Share your failures
- Be curious and kind
- Offer your wisdom and seek it in others

#### Benefits
- We get stronger over time as weaknesses are found and addressed
- We can move fast, and try new things - without fear
- An increased pool/source for solutions to problems
- Psychological saftey
- Easier to identify and eliminate holes in knowledge
- Shared knowledge and increased growth at individual level

#### Anti-patterns
- Blame shifting
- Knowledge siloing
- Hero culture


#### No blame culture

things go wrong. production, inevitably, breaks. when there is a problem, the questions we ask are not to place blame. it helps to know who did what, so we know who to go to for more information; all so that we can better understand how to fix what’s broken. once the fires are out (if any), focus shifts to preventing the same thing from happening again in future.
by breaking something, all you’re doing is exposing a weakness in our process. by putting your hand up and communicating *the thing what you done borked*, you’re allowing us to move fast and well informed, to fix it, and minimise the learning cost. this practice, allows us to move fast, experiment, try things that are new or scary .. with due caution, but without fear of what happens when something goes wrong.

#### Share your failures

failure is a valuable learning resource. sharing failures can multiply the learning effect across a wider team; in some cases solutions, or easy fixes .. to turn a failure into a success, can come form unexpected places.

we expect things to fail (want to innovate and be ambitious .. if we’re not failing, we’re being too safe)

#### Be curious and kind

what we’re after, is psychological safety. we want an environment where no individual is afraid to show what they don’t know. take care in choosing the words, and tone of voice you use. if we’re asking questions, it’s to gain understanding.

(PRs don’t be savage, in retros etc. curious rather than judgemental)

#### Offer your wisdom and seek it in others

you don’t know what others don’t know. anyone can learn from anyone else. ask about how things are done, ask a about someones specialty, and share your own knowledge freely.

knowledge sharing is in our culture.

---


### We Care

We care about our customers. Our customers include our friends, our families and our loved ones. Our customers can be deeply personally affected if we do our job wrong.

We care about what we create. We have pride in our work and aim to build products that our customers hold in high regard.

#### Security

Security is not an afterthought.  We take the security of our systems seriously knowing that failures can have serious ramifications for our customers.

##### Practices

* We keep up to date with common security issues (including the OWASP top 10)
* When creating a new system, or modifying an existing one, we consider how it can be made secure
* We aim to make systems secure by default, and have security in depth

##### Anti-Patterns

* Assuming that another team will make your api secure
* Using out-of-date software

#### Data

Keeping our customers' data safe is critical. We have a great deal of highly valuable data that our customers entrust us to keep safe and only use for their benefit.

##### Practices

* We don’t log or store customers personal data unnecessarily
* We report any data issues we find to the #data-issues channel in slack

##### Anti-Patterns

* Storing data without considering ICO and GDPR practices
* Logging personally identifiying data 

#### Treating Customers Fairly

We don’t prefer one customer over another; on purpose or by accident. The systems we build are created to be blind to who’s using them and non-discriminatory. Where we can, we provide less able customers with the best experience we can.

##### Practices

* We follow web standards, and provide accessible options where possible
* Customers with different devices are treated equally 
* We investigate errors and seek to rectify situations where things go wrong. We don’t have “unlucky” users.

##### Anti-Patterns

* Low contrast text that some customers can't read
* Not fixing a customers account because a bug didn't affect many people
