## Ride Sharing Information Security

### 1. Design the system components of a drive sharing application (ex: Uber, Lyft). Specify what elements are necessary for this application to work.

- Your design must include a block diagram of each of the components to have the application needs to operate.

- In your design, you must provide a list of the data that you need to collect for the operation of the application. For each, provide a description of why you need this data. Examples:

  - who are the users of your application? what kind of information do you need of each of them?

  - ![image-20231209100945732](.\images\image-20231209100945732.png)

    ![image-20231209100336909](.\images\image-20231209100336909.png)

    ![image-20231209101024274](.\images\image-20231209101024274.png)

  - what data do you need to make the user experience better? Examples: better ride experience, shorter wait time, faster routes, etc

    ![image-20231209100421674](.\images\image-20231209100421674.png)

    ![image-20231209101721044](.\images\image-20231209101721044.png)

    ![image-20231209101753136](.\images\image-20231209101753136.png)

  - what kind of data do you need to collect to measure the performance and efficiency of the application?

  - ![image-20231209101859993](.\images\image-20231209101859993.png)

  - ![image-20231209100502794](.\images\image-20231209100502794.png)

  -

  - ![image-20231209100758507](.\images\image-20231209101849781.png)

  - what about payment and tipping?

  - ![image-20231209101358851](.\images\image-20231209101358851.png)

  - ![image-20231209101442137](.\images\image-20231209101442137.png)We need information about demand in the Redis database. Spark allows to set the demand data in redis.

- Include a privacy design for the application.
  - For all the data that is being collected, what can be seen and by whom?
  - What information should have restricted access?
  - what information should not be seen by anyone?
- Assume you are a pen-tester and you are in charge of testing the privacy design proposed.
  - What are the risks if you are able to get access to the app as a user, as an admin, and as developer?
  - In any of these cases, what are the ways that an attacker can provoke a privacy breach? What kind of attacks can be used to accomplish this.
  - Write an ethical analysis of the consequences of a privacy breach of the app for each of the cases above.

### 2. Your drive sharing company has decided to sell users data to advertisers.

- You have been asked to loosen up your design so that data can be sold to advertisers. Additionally, your manager has asked you to provide a list of data that can be sold, so the advertisers can maximize the accuracy of the ads.
- Provide the details of the new privacy design following the same principles you used for the original design.
- Repeat the pen-tester exercise done for the original design.
- Write an ethical analysis of the consequences of selling this data to advertisers.
