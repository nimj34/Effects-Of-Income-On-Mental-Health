#  💸 Effects of Income on Mental Health 🧠

# 👀 See the code [HERE]()

## 📊 Skills Showcased

## 🤷 Research Question
"How does income influence suicidality?"

## 🔎 Hypotheses
1. Lower income leads to higher depression, which in turn leads to suicidal thoughts.
2. Lower income leads to higher depression, which in turn leads to suicide attempts.

## 📖 Variables
The data that I used was collected from the [National Longitudinal Study of Adolescent to Adult Health](https://addhealth.cpc.unc.edu/) (Add Health). This is a longitudinal study that originally took place in five separate waves. For the purposes of this project, however, I focused on Wave III which took place between 2001 and 2002 and Wave IV which took place between 2008 and 2009. 

The final dataset after cleaning and merging both waves had 1659 rows and 24 columns.

### 1. **SEX**- respondent's sex
Values:

* 1 = MALE
* 2 = FEMALE

### 2. **AGE**- respondent's age
Values:

* Range between 18 and 33

### 3. **INCOME**- Thinking about your income and the income of everyone who lives in your household and contributes to the household budget, what was the total household income before taxes and deductions in 2006/2007/2008? Include all sources of income, including non-legal sources
Values:

* 1 = Less than $5,000
* 2 = $5,000 - $9,999
* 3 = $10,000 - $14,999
* 4 = $15,000 - $19,999
* 5 = $20,000 - $24,999
* 6 = $25,000 - $29,999
* 7 = $30,000 - $39,999
* 8 = $40,000 - $49,999
* 9 = $50,000 - $74,999
* 10 = $75,000 - $99,999
* 11 = $100,000 - $149,999
* 12 = $150,000 +

### 4. **DEPRESSION**- during the past seven days, you felt depressed
Values:

* 0 = Never or rarely
* 1 = Sometimes
* 2 = A lot of the time
* 3 = Most of the time or all of the time

### 5. **SUICIDE_THOUGHTS**- during the past 12 months, have you ever seriously thought about committing suicide?
Values:

* 0 = NO
* 1 = YES

### 6. **SUICIDE_ATTEMPTS**- during the past 12 months, how many times have you ever actually attempted suicide?
Values:

* 0 = None
* 1 = Once
* 2 = Twice
* 3 = 3 or 4 times
* 4 = 5+ times

### 7. **PARENT_PUBASSIST**- before you were 18 years old, did anyone in your household ever receive public assistance, welfare payments, or food stamps?
Values:

* 0 = NO
* 1 = YES

### 8. **PARENT_HOWMUCH_PUBASSIST**- during how much of the time before you were 18 years old did anyone in your household receive this kind of help?
Values:

* 1 = Only a very short time
* 2 = Less than half the time
* 3 = About half the time
* 4 = Most of the time
* 5 = Practically all the time
* NA = Responded "NO" to **PARENT_PUBASSIST**

### 9. **CURRENT_WORK**- are you currently working for pay at least 10 hours a week?
Values:

* 0 = NO
* 1 = YES

### 10. **HOURS_WORKED**- how many hours a week do/did you usually work at this job or your most recent job?
Values:

* Range between 4 and 98 hours
* NA = answered "NO" to **CURRENT_WORK**

### 11. ***FRIEND_FAMILY_SUICIDE**- during the past 12 months, have any of your family or friends tried to kill themselves?
Values:

* 0 = NO
* 1 = YES

### 12. **FRIEND_FAMILY_SUICIDE**- have any of them died as a result?
Values:

* 0 = NO
* 1 = YES
* NA = Answered "NO" to **FRIEND_FAMILY_SUICIDE**

## 📉 Findings

