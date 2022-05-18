# We Care - Engineering Principle

[Back to Engineering Principles](../engineering%20principles.md)

We care about our customers. Our customers include our friends, our families and our loved ones. Our customers can be deeply personally affected if we do our job wrong.

We care about what we create. We have pride in our work and aim to build products that our customers hold in high regard.

## Security

Security is not an afterthought. We take the security of our systems seriously knowing that failures can have serious ramifications for our customers.

### Practices

- We keep up to date with common security issues (including the OWASP top 10)
- When creating a new system, or modifying an existing one, we consider how it can be made secure
- We aim to make systems secure by default, and have security in depth

### Anti-Patterns

- Assuming that another team will make your api secure
- Using out-of-date software

## Data

Keeping our customers' data safe is critical. We have a great deal of highly valuable data that our customers entrust us to keep safe and only use for their benefit.

### Practices

- We don’t log or store customers personal data unnecessarily
- We report any data issues we find to the #data-issues channel in slack

### Anti-Patterns

- Storing data without considering GDPR
- Logging personally identifiying data

## Treating Customers Fairly

We don’t prefer one customer over another; on purpose or by accident. The systems we build are created to be blind to who’s using them and non-discriminatory. Where we can, we provide all customers with the best experience we can.

### Practices

* We follow web standards, and provide accessible options where possible
* Customers with different devices are treated fairly
* We investigate errors and seek to rectify situations where things go wrong. We don’t have “unlucky” users.

### Anti-Patterns

- Low contrast text that some customers can't read
- Not fixing a customer's experience because a bug didn't affect many people