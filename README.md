# HOMEWORK #2 - PORTFOLIO - PABLO ZAMBRANO

Page of the deployed app:

'''
https://pfzm.github.io/HMW2/

'''


## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Normalize CSS

```
Normarlize.CSS from: https://necolas.github.io/normalize.css/
```

## Issues found:

- The display of the "articles' when the links are click in the nav bar wasn't showing propperly as the header is set with an sticky position. meaning the 'main' was offset. After doing some research this was fix adding the following code:

```
article::before {
    display: block;
    content: ' ';
    margin-top: -180px;
    height: 180px;
    visibility: hidden;
    pointer-events: none;
  }
```



## Future updates that needs to be done:

- Form needs to be fix need to be functional

- Font Size looks to small on mobile devices.

- Update poject section with my projects

- Update CV and LinkedIN
