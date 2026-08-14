# motor-maintenance
AI project that predicts faulty component in a motor before it happens
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course, electric motor maintenance 

## Summary

This is a system that predict the faulty part of a brushless motor before it actually becomes faulty. it uses data from the motor such as time used, current, voltage, temperature, vibration, etc.


## Background

* it solves the problem of motor being faulty and causing accidents or expensive repairs
* it solves the problem of motor life since it predicts the faulty component such that the engineers can replace that part before it causes other problems and bigger repairs.
* the motivation for this project is my personal field of study, I study in engineering and we use motors all the time. And they fail and break all them time, therefore a system to handle the maintenance of the motors is extremely helpful for a complex system.


## How is it used?

This system can be used in various situation. it can be used in any machines containing a motor. engineers and the users of the machines are the main target audience. the systems reads data from sensors in the motor and predicts a trend. this trend is then used to predict when and what part of the motor is going to break before it happens.

![Brushless motor]()

If you need to resize images, you have to use an HTML tag, like this:
<img src="data:image/jpeg;base64,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">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
