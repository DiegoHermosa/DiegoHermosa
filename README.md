# Coupon Investigation

For my own investigation, I selected the Restarants(20-50) coupons for analysing the driver characteristics which have influenced the acceptance of coupons. I reviewed various factors such as the age, income, passenger type, and marital status and time.

## Conclusions
1. **Age:** the young (under 30 years) and single drivers are who accept the most of this type of coupons.
2. **Income:**
   About the income, I analyzed the data by filtering in 3 groups: high($50.000 to $100.000 or more), medium($25000 to $49999) and low income(under $25.000).
3. **High income**: in this group the single and married partner accepted the most of coupons, which seems a normal behavour for them. Interesting to see the divorced people have not accepted this coupon in this group.
4. **Medium income**: the singles keep at the top of the coupon acceptance and then the married and unmarried are in the second place, both have a wide age range whichs looks like a normal behaviour.
4. **Low income**: again, the singles and young keep on the top of coupon acceptance.
5. **Passenger type**: The driver  who accepted the coupons have not passanger, they were alone.
6. **The time of day for acceptance**: 7 AM, 10 PM and 6PM are the top 3. 

## Data review
### Proportion of acceptance coupon
The acceptance of this coupon is less than the 50 %

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/15292c7d-b6d8-47ca-b411-ad4311b7dad6)

Compared to the cheap restaurant, the restarant(20-50) has very low acceptance

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/effb9d02-2cc1-4d21-96ee-be5a6a99eaa5)


### Age
The age have a notorius impact on the coopon acceptance, showing that under 30 years old are the drivers who most accept this kind of coupon

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/363d0a6a-18e1-42f4-bd12-d44a88295b68)

### Income, Marital status and Age

Both factors are very important in the acceptance rate. About the income, I analyzed the data by filtering in 3 groups: high($50.000 to $100.000 or more), medium($25000 to $49999) and low income(under $25.000). the next plots show the distribtions of the acceptance.
![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/2a3d6e9e-6733-4127-8440-8c70c8c49fb3)

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/78b965fe-b965-47fe-85ca-7b48386629d0)

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/117f033b-f636-4bbc-8e8c-b0962aa5f239)


### Passenger type

Most of the driver were alone when accepted the coupon, this could be explained by the time of acceptance: 7 AM, 10 PM, both could time for breakfast(startting to work?) and dinner (finishing a long day?) , also the income could have impact on this, spending less money?.

![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/cccdc9ac-831e-42ea-a236-3c294ee10b3c)


### Time.
The 7 AM, 10 PM and 6PM are the top 3 for time acceptance, could be these ones for breakfast and dinner, I was expecting to see the lunch time too in the top, but it's not in the dataset for any record.
![image](https://github.com/DiegoHermosa/MLAICourse_m5/assets/160977826/1fd6dd00-5963-4c77-8d89-1be1dfb036c3)


## Next steps and recommendations:
**1. Improve the data dictionary and questions**: each attribute should have its own description, by improving this will help getting a better understanding of the asked questions. Some questions was too ambiguos causing confusion and making assumptions which could generate unaccurate analysis and results.

**2. Do more data cleaning and transformations**: there are a lot of attributes which are strings storing categorical values and ranges, it would great to transform them to numeric values.




