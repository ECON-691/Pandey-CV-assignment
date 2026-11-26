# ECON 691: Using LaTeX to Make a CV

## Description & Purpose

In this assignment, you will use your nascent TeX programming skills to make a Curriculum Vitae or CV from an existing template. Such a document lists your accomplishments and qualifications in the field in more length and detail than a résumé does. Jobs may ask for one or the other, and academic/research-oriented jobs greatly favor the CV. Since you will need such a document when the time comes for you to be on the job market, might as well make a nice one now and have it ready to update when the time comes!

Contrary to common opinion, many jobs - particularly those in the academic sphere - actually like seeing a plain document that clearly lays out qualifications. Simplicity is key. Here are some rules on design from [The Professor Is In](http://theprofessorisin.com/2016/08/19/dr-karens-rules-of-the-academic-cv/). This assignment follows the vast majority of these guidelines.

## Instructions

I have made a template for the Job Market CV for the students on the job market, and I want you to work with it to make a non-job market CV. There are elements of the JM CV template should be ```%commented out```, so that you remember them for the future but make them disappear for now -- for instance, your home address is something goes on the JM CV, but not on a general CV; same with the Job Market Coordinator information. (Don't just delete the info! Commenting out lets you keep the info and structure in the code, while preventing it from showing on the PDF.)

I have included an abbreviated version of my own CV in this folder as the template/example for you to follow. (FYI: it makes a school look really good when candidates all have standardized CVs!) Since you are at the start of the career, you might feel like you don't have a lot to fill in yet, but that's ok. What I really want is for you to have a document that you have started, and that you can start adding things to as you continue. For this assignment, the most important thing is for you to follow the same design and layout elements as the template.

### Getting Started

1. *Make a new branch:* Using your knowledge of GitHub, make sure to create a new branch and call it ```assignment```.
2. *Launch the codespace:* Open a new codespace on your ```assignment``` branch; the WebLaTex in this repo should generate a VS Code editor like you've seen in class.
3. *Edit the CV:* Keeping these instructions open in one tab and the ```cvexample.pdf``` file open in another tab, work on updating the file ```jobmarketCV.tex``` in a third tab in the codespace according to the following instructions.

### Modifying the Header Section
1. *Update the PDF keywords:* Make sure to update the ```\def\name{Your Name}``` with your name and the ```\hypersetup{  }``` with your (anticipated) fields.
2. *Update the footer:* Find the command ```\lfoot{ \fancyplain{}{Your Name}}``` and update it with your name.
3. *Update the contact layout:* Your contact information should be formatted in two columns (minipages) like this:
   - Left minipage:
     - Department of Economics
     - Northern Illinois University
     - 515 Zulauf Hall (this is the econ front office)
     - DeKalb, IL 60115
   - Right minipage:
     - Office: DuSable 470 (this is the TA office)
     - Email: youremail@niu.edu
     - Homepage: your-website (if applicable -- you can use your GitHub Jekyll site)  
       *Pay attention to how links are done in LaTeX; see more [here](https://www.overleaf.com/learn/latex/Hyperlinks).*
     - ORCiD: if you do not yet have an ORCiD, consider registering at [orcid.org](https://orcid.org/register). Otherwise, comment this out.  
     
4. *Remove job market specific elements:*
   - **Comment out (don't delete!)** the following sections using %:
     - Your home address
     - Your citizenship status
     - Your mobile number 
     - The Job Market Coordinator section
     - The Job Market Administrator section
   - Keep these commented sections for future reference when you go on the job market

### Completing Other Sections
1. Input your own information following the style of the template.
2. The dissertation committee section is important on the job market, but it is not needed on this CV. Comment out this section header and everything in it.
3. For categories where you don't have entries yet:
   - Keep the section headers
   - Write "Not yet" or "Not applicable"
   - Don't remove or comment out these sections - you'll need them later!
4. The "PUBLICATIONS" section must remain, even if empty
   - You may skip subheadings like "Grants" or "Refereed Journal Articles" if you do not have anything to include in them
   - Please make sure to keep the "Manuscripts in Preparation" and "Research in Progress" sections, even if you just write "Not yet" underneath them.
5. Do your best to fill in all the categories that are already present on the example CV. Don't make anything up though! If you truly have nothing to write in that category, you may write "Not applicable" or "Not yet!" I have left some of my papers/presentations in only as examples for you; please delete them from your own.

#### Frequently Asked Questions

1. *Can I include other things on this CV?* Yes! Please use this template and fill it out to the best of your ability. If you have any other areas that you would like to highlight, you may do so, as long as they complement the current style. (After you turn in the CV template, you can fork this repo to your account and continue updating your CV for internships and other.)
2. *Can I include my computer skills?* Yes, you should! This is recommended in the template.
3. *Can I add more packages?* I would recommend against this -- they are not needed.

### Submitting Your Work
1. *Commit your changes:* While working in Codespaces, make sure to correctly **stage** and **commit** your changes following a session coding. Make sure your commits have clear, descriptive messages, and that you commit regularly (don't leave uncommitted changes in your Codespace!)
2. *Review prior to submission:*
   - Ensure your CV compiles without errors
   - Check that all unnecessary sections are properly commented out
   - Verify your formatting matches the template style
3. *Create a Pull Request:* 
   - Create a PR from your `assignment` branch to `main`
   - Title it "LastName CV Assignment"
   - In the PR description, note any sections you struggled with or feel confident about
   - Merge your pull request and prune the `assignment` branch

## Need Help?

If you encounter any issues:
1. Check the LaTeX error log
2. Verify your syntax against the template
3. Contact the instructor if you need clarification by submitting a comment on the special `feedback` pull request created when you accepted the assignment (do **NOT** merge this pull request - leave this one open for questions you may have)

## Grading
- **GitHub Submission:** You will receive 10 points for having successfully submitted the assignment via pull request; even if you work on the assignment and create the CV, if you do not submit it according to the instructions, you will not receive these 10 points.
- **LaTeX Code:** Your code will be graded out of 10 points on a completion basis, double checking that it compiles with no errors in Codespaces (make sure to look at the log!) and that you have ```%commented``` out the unnecessary pieces instead of deleting them.
- **CV Document:** Your CV document itself will be graded out of 10 points on 1) how well it matches the example style and 2) how relevant the details you included are.

## Additional Resources
Here are some web links to assist you with how to write a CV. Focus on the first two:

- NIU Career Services (more geared toward undergraduates, but still relevant):  https://www.niu.edu/careerservices/career-resources/resumes.shtml
- University of Illinois (geared toward graduate students):  https://grad.illinois.edu/sites/default/files/PDFs/CVsamples.pdf
- (Optional) Harvard (geared toward econ PhDs on the job market):  http://economics.harvard.edu/files/economics/files/cv_guide.pdf


