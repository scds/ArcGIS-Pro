---
layout: default
title: Common Elements
description: SCDS Do More with Digital Scholarship workshop series
nav_order: 100
---

# Common Elements
{: .no_toc }

Below are a bunch of common elements and their source code. Click the copy button at the top right of a codeblock to copy it to your clipboard.

More general markdown elements can be found [here](kitchen_sink_DELETE).

Remember to delete this page before publishing.

# Table of Contents
<div class="code-example" markdown="1">

<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

````md
<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>
````

{: .note }
> You can only have one table of contents per page.

</div>

***
<!-- -------------------------------------------------- -->

# Question and Answers
<div class="code-example" markdown="1">

This is a simpler way to ask a question with an answer.
<details>
    <summary> See Answer. </summary> 
    <blockquote>
        Your answer goes here. <br>
        Multiple lines.
    </blockquote>
</details>

```md
This is a simpler way to ask a question with an answer.                         <!-- Question Text -->
<details>
    <summary> See Answer </summary>            
    <blockquote>
        Your answer goes here. <br>                                             <!-- Answer Text -->
        Multiple lines.
    </blockquote>
</details>
```
</div>

<div class="code-example" markdown="1">
{: .new-title }
> Exercise 1
> 
> This is a fancier way to display questions.
> 
> You can also have multiple lines.
>
> <details>
>   <summary> See Answer </summary>
>   <div markdown="1">
>   {: .note-title }
> > Answer
> > 
> > You can put your solution here
> >
> > Multi line solutions
>   </div>
> </details>

```md
{: .new-title }
> Exercise 1                                           <!-- This is where you edit the title -->
> 
> This is some really long question.                   <!-- Question Text -->
> 
> So long you might need a second line.                <!-- Optional Additional Text -->
>
> <details>
>   <summary> See Answer </summary>
>   <div markdown="1">
>   {: .note-title }                                   
> > Answer
> > 
> > You can put your solution here                     <!-- Answer Text -->
> >
> > Multi line solutions                               <!-- Optional Additional Text -->
>   </div>
> </details>
```
</div>

## H5P

Alternatively, you can use H5P to create questions and other cool interactive components.

McMaster has access to eCampusOntario's H5P server, where you can create and host your questions on. 

<https://h5pstudio.ecampusontario.ca/>

Simply sign up with your McMaster email, create an interactive component, and copy the embed code into your Markdown file.

<div class="code-example" markdown="1">

<!-- Script to resize H5P elements. Put this at the top of your Markdown file, below your preamble -->
<script src="https://h5pstudio.ecampusontario.ca/modules/contrib/h5p/vendor/h5p/h5p-core/js/h5p-resizer.js" charset="UTF-8"></script>

<!-- H5P Embed. put this where you want it to be seen -->
<iframe src="https://h5pstudio.ecampusontario.ca/h5p/57291/embed" style="border: solid 2px #7a003c" width="100%" height="350" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

```md
<!-- Script to resize H5P elements. Put this at the top of your Markdown file, below your preamble -->
<!-- If you're using multiple H5P elements... only use this line of code ONCE! -->
<script src="https://h5pstudio.ecampusontario.ca/modules/contrib/h5p/vendor/h5p/h5p-core/js/h5p-resizer.js" charset="UTF-8"></script>

<!-- H5P Embed. put this where you want it to be seen -->
<!-- Make sure to edit your width to be 100%, and add the style border there. -->
<iframe src="https://h5pstudio.ecampusontario.ca/h5p/57291/embed" style="border: solid 2px #7a003c" width="100%" height="350" frameborder="0" allowfullscreen="allowfullscreen"></iframe>
```

</div>

***
<!-- -------------------------------------------------- -->

# Input Output Code Blocks
<div class="code-example" markdown="1">

{: .label }
Input
```python
a = 3
b = 4

c = sqrt(a^2 + b^2)
print(c)
```

{: .label .label-green }
Output
```
5
```

---

````md

<div class="code-example" Markdown="1">

{: .label }
Input
```python
a = 3
b = 4

c = sqrt(a^2 + b^2)
print(c)
```

{: .label .label-green }
Output
```
5
```
</div>
````

</div>

***
<!-- -------------------------------------------------- -->

# PDF Viewer
<div class="code-example" markdown="1">

<embed src="assets/docs/examplePDF.pdf" style="border:none;" width="100%" height="466px">

---

````md
<embed src="assets/docs/examplePDF.pdf" style="border:none;" width="100%" height="466px">
````

</div>