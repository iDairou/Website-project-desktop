![a screenshot presenting the front page of the project website](./assets/demo.png)

# Desktop Website Project

 Website project is a landing page modeled after [Themewagon free Nova template](https://themewagon.com/themes/project-app-showasing-onepage-bootstrap-template-free-nova/). 

See [LIVE](https://idairou.github.io/Website-project-desktop/).


## Process

The main goal was to implement code using BEM methodology and set styles for every section using partial .css files.

## Solutions provided in the project

- I implemented styles focusing on common properties of different classes. That's why after implementing `reset.css` file to reduce browser inconsistencies i created `base.css` file to put there all the common styles i used in project.

- File `_colors.css` contains root selector that is reusable on few text elements on the website.

- Individual styles for every section I created in separated `.css` files to make clear and easy readable architecture of the project.

- The website is focused on centered sections and elements that's why i used common class that centers elements where it's needed.
 ```
 .flex-center {
	display: flex;
	justify-content: center;
	align-items: center;
}
```

## Conclusions for future projects
During process of creating this project I understood why BEM and css files components are so important to have good structure of the project. If i would need to change anything in few months on this website i wouldn't have any problem to find potential issue in code.



## Thanks
- To my [mentor](https://github.com/devmentor-pl) for creating the task and for the code review.
