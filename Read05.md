### Hello everybody from Read05, about CSS.

One of the most interesting topics in web development. Which allows you to style your web pages by changing backgrounds, fonts, colors, aligns, spaces, directions, and many more.

**There are three ways to put your CSS code in:**

**1.** External file --> a separted file only for css, and its extension is **.css** for example style.css (The best way)

**2.** Internal file --> it placed in the same HTML page in the head section, we put the style tag and write the content between the open and closed tags. such as: **<style> ... </style>**

**3.** Inline style --> it becomes inside the tag itself (The worst way)

**What about CSS syntax?**

**In general** --> selector{property:value}

**but if you want to know it in details, continue reading:**

**External file**

we put the selector or the class or ID that we want to apply the style on, then we apply the rule **{property:value}**

for example: 

body { font-family: Arial, Verdana, sans-serif;} h1, h2 { color: #ee3e80;} p { color: #665544;}

**Internal file**

  <head>

    <style>

      body{
        background-color: blue;
      }
      
    </style>
    
  </head>

**Inline style**

in the tag itself we put the style, such as: <p style="color:gray; text-align: center;"> ----- </p>
