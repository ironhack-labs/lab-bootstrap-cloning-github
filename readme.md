![](https://i.imgur.com/1QgrNNw.png)

# Cloning with Bootstrap

## Introduction

In this lesson we are going to create our own "Bootstrap version" of GitHub. We will recreate the **Issues** page for Airbnb's CSS repository on GitHub using only Bootstrap styles and components. See the original on GitHub: https://github.com/airbnb/css/issues.

At the end of the lesson, your GitHub will look something like this:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_366f12c1fab910ed8fd7ece9c7735371.png">

As we said, we will use Bootstrap [Styles](http://getbootstrap.com/css) and [Components](http://getbootstrap.com/components/), and we won't have any CSS file in the project!

### Requirements

- [Fork this repo](https://guides.github.com/activities/forking/).
- Clone this repo into your `~/code/labs` folder.
- You can't use your own styles.

### Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin master
```

Navigate to your repo and create a Pull Request -from your master branch to the original repository master branch.

In the Pull Request name, add your campus, name, and last names separated by a dash "-"

### Starter code

Your starter code contains just one HTML file with the following content:

- Basic HTML structure to start working on the exercise.
- Link to the `jQuery` CDN, required by the Bootstrap Components.
- Link to both Bootstrap Styles and Components.

You can find all the links in the `<head>` tag:

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
```

## Iteration #1: Menu

First of all, we are going to build our application's menu:
<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4513d3ad0a3631cf0728ec3e994d8951.png">

We will use the [Grid System](http://getbootstrap.com/css/#grid) to split the content in two different columns. The menu bar can be created by using the [Navbar](http://getbootstrap.com/components/#navbar), that contains the nav bar itself and the different dropdown menus that you will need.

As you can see, we are using some glyphicon icons. Here are the names of the icons we are using:

- Bitcoin
- Bell
- Plus
- User

Now let's add some more complexity to this iteration by creating the different dropdowns that you have in the original GitHub:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_80208920739b1c46a348327fbb92629b.png">

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c6c056c3768215bb3d6030ed1120aa7d.png">

The Navbar documentation shows you how to create a dropdown, so you have all you need there to create the site.

The last thing you have to consider is that the menu doesn't have to take the 100% width of the page. You can avoid this by using the [`container`](http://getbootstrap.com/css/#overview-container) class in the navbar. :smile:

## Iteration #2: Repo Header

In the second iteration, we are going to create the header of the repo:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4774d5e06cf80026ce2648472ae50356.png">

There is a new component here that you have to use, [Input Groups](http://getbootstrap.com/components/#input-groups). This will help you create the different controls you have in the right side of the header.

Again, we give you a list with the different icons you will need to complete the iteration:

- Book
- Eye Open
- Star
- Link

<!-- :::info -->
**Note**: You will need more components and styles to complete this iteration. All of them have been used in the previous iteration. Think about what you will need to compose our header. :smile:
<!-- ::: -->

## Iteration #3: Tabs & Filters

In this iteration we will create the [Tabs and Nav Tabs](http://getbootstrap.com/components/#nav) we have in the page to let the user select the different sections of the project:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f29689b6c8010451cc84c0408ee69ae.png">

As you can see, this iteration also includes some [Buttons](http://getbootstrap.com/css/#buttons). Check out the different styles you can apply to have a green button. To create the buttons that are located at the right side of the search box, you will have to use the [Button Groups](http://getbootstrap.com/components/#btn-groups).

Finally, it may be interesting to use the [Grid System](http://getbootstrap.com/css/#grid) to lay out the filters section.

The icons you will need to complete this iteration are:

- Menu Left and Menu Right
- Exclamation Sign
- Option Vertical
- Th List
- Resize Horizontal
- Equalizer

## Iteration #4: Table

In the next step of our development, we will create the table with all the issues of the repository:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_dd0cc8152b96a62c96dc9ff3ff7acfe6.png">

Let's start by wrapping the content in a [Panel Body](http://getbootstrap.com/components/#panels) that will help us to create the bottom line of the section. Then, we will have to create a [Table](http://getbootstrap.com/css/#tables) with its rows and columns. You can set the background color of the first row by adding the `active` class to it.

At the bottom of the table, you will have to [align the text correctly](http://getbootstrap.com/css/#type-alignment) to add the **ProTip**. To complete this iteration, you will need the following icons:

- Exclamation Sign
- Ok
- Flag

## Iteration #5: Footer

Last, but not least, we will create the footer of the application. That should be pretty simple compared to the other steps:

<img style="border: 1px solid black" src="https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_52d8ad0d4487264a060009860d995d07.png">

You will need to use the [float classes](http://getbootstrap.com/css/#helper-classes-floats) to arrange the different links to the left or right. Finally, we have to place the Bitcoin icon at the center of the footer. You'll have to do that on your own.

<!-- :::info -->
**Tip**: You don't need the Grid System to arrange the footer content. :smile:
<!-- ::: -->

// Happy coding!
