# Redefining How Contractors Get Paid

Let’s say John gets paid about $2,000 a week. He writes down 4 goals to accomplish in that week. On Sunday, our system figures out how many of the goals and transfers the money to his account. For instance, $1,500 gets transferred if he accomplishes 3 out of the 4. With exceptional performance, he could be paid $2500 (bonus included).

For any employee using git (Engineer, Designer), the system will know whether he/she accomplished an awaited goal/task/milestone when his work (code, bug fixes, design) has been reviewed by the team lead or other employees and then finally gets merged to master.

This has trust incorporated because git is a decentralized version control system. Any commits to master or public branches can be reviewed by anybody.

### Spec

The application parses the git commits then transfers the amounts for any awaited task accomplished.

```
    **********           *********************           ***************
    *  Git   * --------> *  Application code * --------> * Payment API *
    **********           *********************           ***************
```

> Bigger vision: Companies might only need 10% employees 90% contractors. The individual has way more freedom on when, where, how to work.

#### Implementation

This could be built on top of Github as it already has peer-review, webhooks, and other useful features.

With code analysis tools and the history of tasks accomplished by every contracter. Step one, goals/milestone generation, could be semi-automated.

#### Possibilities:
- Companies and individuals will no longer be reactive. They will be forward looking.
- This could be extended to how open source software gets developed.
- Automates bug bounties
- The wave of digital nomads: anybody just needs a computer and internet
- As Github is becoming more beginner friendly even the average worker / artist will be able to make edit a document with the appropriate commit message and get paid automatically once reviewed