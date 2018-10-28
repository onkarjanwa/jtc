**Jalan Technology Consulting** works with enterprises across the globe to provide great technology solutions. At JTC, there are two types of roles:
- Software Engineers: They work with clients and deliver world class scalable software solutions. 
- Technology consultants: They identify opportunities in a sector, work with engineering team to build proof of concepts, and help clients win.

We are an output driven organization and deliver what we commit. Other than working from our office, we also welcome people to work remotely with us as a full time employee (NOTE: no part time and/or freelancing and/or contracting).

The rest of the document talks about our values and how we function. If you have any feedback on how we can improve, please write to Jai at jjalan@jalantechnologies.com

## Mission
Help businesses win by providing best possible technology solutions.

## Values
- **Honesty**: Being honest is the only way to become trustworthy and be reliable to your team and your clients. If you are stuck, going through rough time or made a mistake, speak up. It's always the right thing to do.
- **Independent**: We look for people, who can solve problems and work independently. We are not good at handholding.
- **Passionate**: Be passionate about what you do. If you are not, you will not succeed. We enjoy working with passionate people. If you stopped enjoying what you do at JTC, talk to your manager.
- **Deilvering commitments on time**: Commit. Deliver. It is almost impossible to run a company if your team members and your clients cannot rely on you.
- **Strong work ethics**: Work matters. It puts food on the table as well as bring meaning to our life. If you are working with us, bring your A game. If you are considering freelance or work part time with other firms along with a full time job with us, please talk to your manager beforehand. In our experience, this almost never works. If you want to broaden your horizon, talk to your manager. We often encourage giving back to community and can help you identify right open source projects to contibute.
- **Do not give up**: From time to time, you will find yourself in a situation that may be out of your comfort zone. Do not give up. Ever. Push yourself and you will win.
- **Team player**: Appreciate, if someone did good. Help them improve by giving them constructive feedback when you see an opportunity for your team members to grow.

## About us
Jai started JTC in 2016 after realizing that there are lot of businesses who are always looking for reliable technology partners to help them deliver solutions. Before JTC, he spent a decade working with Microsoft, Google, Startups where he lead engineering teams.

Our primary nature of business is technology consulting and implementation of software systems. Our technology consultants brings clients on board by pitching software solutions and our software engineers work with clients to deliver them. We do not have frontend engineers, backend engineers, project managers. Our engineers take full ownership of features and work alongside with customers to deliver.

We often work on few products of our own as well. If you are looking to work with us, talk to your hiring manager to learn more about our works.

## Engineering:

### Interview process
Our interview process for an engineering role generally consists of three steps:
- Build a 'Hello World' like application using ME(A/R)N stack. We usually expect it to be done within 24 hrs. However, if you are new to the stack, we expect it to be done in 72 hrs.
- An online interview (45 minutes long) with an engineer at JTC. Interview involves solving a problem and writing code.
- We may sometime ask you to write a blog to demonstrate your ability to express complex technical solutions in an easy to understand manner.

If everything goes well, we will make you an offer.

### Software development process
We follow the agile methodology. It all starts with sprint planning. Team members get together on a particular day of a week (Monday in our case), talks about new user scenarios that need to be enabled as well bugs, if any, that needs to be addressed. The work is estimated in story points and planned (factoring any upcoming time offs) for the sprint. Our sprint is usually a week long. All the work is managed in JIRA.


We use Gitflow branching model and Github for source control. For every task, bug, or story, we create a feature branch. Ex: Consider a story in JIRA:  SEQP-10 – User should see an error message if they entered wrong username or password.
```
git hf feature start SEQP-10/error_message_wrong_username_password
```

We use Hubflow (a set of helper scripts) that does all plumbing work to enforce Gitflow branching model. Once all the changes are made and automated tests are written, changes are committed.

Before a commit can be made locally, our bot ensure that changes follow coding standards and run all automated tests to ensure the changes do not break existing scenarios. In case it breaks, our system does not allow the commit.

At this stage, the engineer who made the change goes to Github and raise a pull request (PR). With each PR, they write a detailed description of the changes made, document manual test cases ran, automated tests cases added, and various devices the changes were tested. S/he then assigns relevant engineers to review the code. Our system automatically deploys just those changes to a new endpoint (for web-based projects). Each PR goes through a detailed code review. Here are a few things a reviewer looks for:

1. Reviewer tests the changes on the endpoint to make sure it does what it was supposed to do.
2. Proper comments have been added to the code.
3. Variables and functions are named correctly.
4. Proper validations and null checks are in place.
5. Relevant automated test cases have been added to cover new code path.
6. Proper error logging is done to ensure we can debug the issue in production in case an issue occurs.
7. The code is architected correctly and follows SOLID design principles.
8. Think about all various scenarios these changes might affect.
9. Does user experience make sense? Is it responsive? Does it render well when user zoom in  or zoom out?
10. Performance implications (time and memory)

Once the reviewer approves the changes, the PR is merged and developer moves on to next tasks. Note that we do not have a separate QA team and our engineers own everything from building the feature to testing and monitoring.

As soon the changes are merged, our system auto deploys them to a staging server. At the end of the sprint, the product owner (often our customer) verifies the changes. Once the changes are verified, we release them to production. We have set up monitors on our servers and if there are any errors, bug or crashes that happens, our team gets immediately notified on a Slack channel. Yes, we use Slack for our team communication.

The project team members do a daily standup to talks about the progress they have made yesterday, what they plan to work on today as well as any blocking issues. This makes sure that everyone is on the same page and any blocking issues are surfaced early on.

## Working at JTC
### Basic Ettiquites
- Be on time. Respect other people time.
- Be patient. Listen first. Understand other's perspective first. Speak after.
- Always be professional in both verbal and written communication, both internally and externally. Use Grammarly if you need help with your written communication.
- If you are on a call, please turn on video in both internal and external communication. It feels pretty weird talking to a computer. Seeing creates a human connection.
- Make sure your profile accurately describes what you do on Slack, Github, LinkedIn, Angel.co including a profile picture. Propespective clients and team members often research about us on internet.

### Perks
 - Competitive salary, paid first week of every month.
 - 2 paid leaves every month.
 - Free beverages, if you are working from one of our office.
 - Macbooks, if you are working from one of our office.
 - An annual offsite for all of us to get together.

### Performance Review
We review your performance primarily based on:
 - Your ability to deliver what you commit on time.
 - Your ability to deliver accurately.
 - Your ability to deliver independently.

#### Promotion
If you deserve a promotion, you will be promoted. To get a promotion, beyond delivering on your commitments on time, we often look at how you went above and beyond to help your team members and your clients to succeed.

#### Under performing
You will be given feedback during 1:1 with your manager. In case you are often missing on your commitments, you will be given few chances to fix it. If not, we will ask you to find an opportunity outside the firm. We also ask you to leave the firm if we find that you lied to us or our clients.

We do have 1 month notice period to help with the transition process as well as give you time to find another job.