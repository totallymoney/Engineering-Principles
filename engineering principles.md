## Engineering Principles at TotallyMoney

---

### Autonomy

- Challenge yourself

---

### We Own It

Ownership is the product of Autonomy, because if you have the freedom to choose you also are more likely to believe in your choices. We decide the pace and quality of our work. We own the problem space and know what problem we are trying to solve for the customer.

#### Practices

- Know the customer
- No deadlines
- Measure your success
- #no-estimates
- Be a part of the product
- Everyone has a voice and can make a contribution

#### Benefits:

- We go at our own pace
- No need to cut corners to make deadlines
- We have control over the quality of the product
- You're unlikely to get blocked for hierarchical reasons
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
- Good test coverage
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
- You can determine the success of a feature

#### Anti-patterns

- Cutting corners to get stuff done
- Imagining what the customer wants without testing your hypothesis

---

### Openness & collaboration

Engineering is a collaborative activity, so share be open and help others where you can. Do not be afraid to show what you don't know. When things go wrong we spend time on achieving tangible, beneficial outcomes, rather than placing blame.

#### Practices

- No blame culture
- Share your failures
- Be curious and kind
- Offer your wisdom and seek it in others
- Maximise learning - from failure, from success, from others
- Pairing
- Build consensus
- Overcommunicate

#### Benefits

- We get stronger over time as weaknesses are found and addressed
- We can try new things without fear
- An increased pool/source for solutions
- Psychological saftey
- Easier to identify and eliminate holes in knowledge
- Shared knowledge and increased growth at individual level
- Prevents incorrect assumptions being drawn

#### Anti-patterns

- Blame shifting
- Knowledge siloing
- Hero culture

---

### We Care

We care about our customers. Our customers include our friends, our families and our loved ones. Our customers can be deeply personally affected if we do our job wrong.

We care about what we create. We have pride in our work and aim to build products that our customers hold in high regard.

#### Security

Security is not an afterthought. We take the security of our systems seriously knowing that failures can have serious ramifications for our customers.

##### Practices

- We keep up to date with common security issues (including the OWASP top 10)
- When creating a new system, or modifying an existing one, we consider how it can be made secure
- We aim to make systems secure by default, and have security in depth

##### Anti-Patterns

- Assuming that another team will make your api secure
- Using out-of-date software

#### Data

Keeping our customers' data safe is critical. We have a great deal of highly valuable data that our customers entrust us to keep safe and only use for their benefit.

##### Practices

- We work with our Legal team to follow GDPR principles
- We don’t log or store customers personal data unnecessarily
- We report any data issues we find to the #data-issues channel in slack

##### Anti-Patterns

- Storing data without considering GDPR
- Logging personally identifiying data

#### Treating Customers Fairly

We don’t prefer one customer over another; on purpose or by accident. The systems we build are created to be blind to who’s using them and non-discriminatory. Where we can, we provide less able customers with the best experience we can.

##### Practices

- We follow web standards, and provide accessible options where possible
- Customers with different devices are treated equally
- We investigate errors and seek to rectify situations where things go wrong. We don’t have “unlucky” users.

##### Anti-Patterns

- Low contrast text that some customers can't read
- Not fixing a customers account because a bug didn't affect many people
