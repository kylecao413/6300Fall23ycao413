# Weekly Report #1

## Section 1: Individual Design Discussion

### Wenyu’s Design

![Wenyu’s Design Draft](./images/wzhou308.png)

**Pros**
- Complete design, with an entry point.
- Intuitive, single class for Comparing Jobs.
- Great use of a boolean to denote current job vs offers.

**Cons**
- Some of the relationships may be incorrect and require revision for simplicity.
- Application interface missing functions to call the rest of the application.
- Redundant jobList in JobList and JobComparison Class.

### Yue’s Design

![Yue’s Design Draft](./images/ycao413.png)

**Pros**
- The design covers all the entities detailed in the requirement.
- The attributes of each class are clear and complete.
- The access specifiers of attributes and methods are correctly chosen.

**Cons**
- The “gymMembership” attribute in “Job” class should ideally be double or float. As indicated in the requirement, this attribute is the monthly allowance on gym membership, ranging from $0-$500.
- The design seems to have missed an entry point as required.
- Function return with type List should not have parenthesis.

### Eddie’s Design

![Eddie’s Design Draft](./images/echaruse3.png)

**Pros**
- The design is concise, complete, and easy to follow.
- The design has an entry point of “User” that ties both “Weight” and “Job” classes together.

**Cons**
- The return type of “compareJobOffers” might not be void as we need the returned results as input to display on GUI.
- Certain namings can be adjusted to be more intuitive. E.g. replace “col” with “costOfLiving” in the “Job” class.

### Kristof’s Design

![Kristof’s Design Draft](./images/kkovacs3.png)

**Pros**
- The design is comprehensive and covers the requirements in detail.
- The design includes an entry point “MainMenu” to tie all aspects of the application and the UI together.
- Protected attributes are used to illustrate different levels of access.

**Cons**
- Certain classes can be combined to make the UML more concise. E.g. “JobComparer” and “JobRanker” can be merged as a single ranker that will be called before a comparison can be made.
- Main Menu class may be redundant and can be combined with the Application Interface.
- Private attributes should be used on some variables for controlled access and encapsulation, which can be achieved through getter and setter methods.

## Section 2: Team Design

![Team’s Design Draft](./images/team.png)

**Commonalities**
- Job class mirrors functionality from Wenyu’s design, which is comprehensive to the design specifications and also cleverly implements the offer functionality with the use of the isCurrentJob boolean to indicate current job vs offers.
- Job List class also mirrors from Wenyu’s design as an intermediary class that ties the interface, jobs, and the comparisons together.
- The Application interface is a combination of Kristof’s MainMenu class + entry point.
- The Job Class implements the adjusted salary and bonus calculation operations from Eddie and Kristof’s designs.
- The Job Class also includes the specificity on the int ranges for the 401kmatch, gym membership, and pet Insurance from Yue and Kristof’s designs.
- Wenyu’s idea to have the settings embedded in the JobComparer was kept, as this the Settings are only ever used by the Job Comparer.

**Differences**
- An entry point through an explicit Application interface as opposed to through another class is a departure from Yue and Eddie’s designs, as we felt this more closely mirrors the requirements.
- Kristof’s offers class was removed as we felt it was solved in a more clever manner by Wenyu’s boolean.
- Wenyu’s Location class was removed as it could be simplified into an attribute of the Job class.
- Eddie’s User class was omitted as this is beyond the scope of the design requirements; however, it may be reimplemented if user customization/multi user access is required further down the line.
- Kristof’s two classes responsible for job comparisons (JobComparer and JobRanker) were combined into a single class which is closer to the other teammates' designs.
- Relationships from Wenyu’s original design were simplified and now more closely mirror the designs of the other team members.
- Multiplicities were changed to more correctly reflect the design requirements and logic.

## Section 3: Summary 

xxxxx
