# RPA Demo
#### This code demonstrates following features

- Document understanding
    > Extacts information from the pay slip of different organisations with different structure.
    > Uses Document Understanding and Intelligent OCR package for acheiving the same.
- Picture In Picture
    > Setting the Target Session property of the workflow as Picture in Picture helps the bot perform the operation in seperate VM like window which is the replica of our PC. This helps the associates and bot function on the same device simultaneously. 
    > Associates can take control of the window if needed which makes this setup perfect for attended automation.
#
#
#

##### Technical Aspect:

#
#


```sh
Action Center would need UiPath.Persistence.Activities

Activities related to Action center should be in Main.xaml. 
This needs to be considered when using REFramework

Picture in Picture cannot be appiled to the subprocess containing the Action Center related activities
```