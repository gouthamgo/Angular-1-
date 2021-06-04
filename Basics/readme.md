# Components of Angular

- Components are the basic building blocks pf an Angular application. An Angular application is a tree of components.
- The root component is rendered when the app loads up.
- Components are composable. Large components can be made from smaller ones.
- When a component renders, it recursively renders its childern components 

## Basics

- A component has a lifecycle managed by Angular
- Angular offers lifecycle hooks that provide visibilty into these key life moments and the ability to act when they occur.
- ngOnInt- called after component initialization 
- ngAfterContentInit - called after the content of a component is loaded 
- ngAfterViewInit- called after the view is initialized
- ngOnDestroy- called just before the component is destroyed and removed from the memory


