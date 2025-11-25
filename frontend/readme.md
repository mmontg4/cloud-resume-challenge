# Frontend Technical Specification

- Create a static website that serves an html resume.

## Resume Format Considerations

I live in the USA. I am not aware of any necessary omissions to comply with discrimination laws. I'm going to use the [Harvard Resume Template format](https://careerservices.fas.harvard.edu/resources/bullet-point-resume-template/) as the basis of my resume.

### Harvest Resume Format Generation
I'm going to let AI do the heavy lifting and generate out the HTML and possibly CSS and from there I will manually refactor the code to preferred standard.

Prompt to Claude:

'''Convert this resume format into html. Please don't use a css framework.
Please use the least amount of css tags
'''

![](./docs/resume_screenshot.png)

This is the [generated output](./docs/resume_template.html) which I will refactor.