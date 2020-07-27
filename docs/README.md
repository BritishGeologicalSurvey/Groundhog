## BGS Groundhog

* [Introduction](main-content/introduction).
* [User Guide](main-content/userguide).

## Have a specific question?

* Use the search bar in the top left to search this documentation
* Check the [FAQ section](other/faq)

## Have an issue?

Raise an issue [Issue Tracker](https://github.com/BritishGeologicalSurvey/Groundhog/issues) 


### Generating the documentation

Convert docx to rst & extract images to folder 
```bash
pandoc -s Groundhog_User_Guide.docx -t rst -o userguide.rst --extract-media=media
```


