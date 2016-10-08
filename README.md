# ns-rotate-change-view
A Nativescript prototype that when mobile rotated, the view with change.

##Why use this?  
Sometimes we need to change the view from 1 column to 2 column when mobile device rotate from portrait to landscape.

##Algorithm:
When mobile rotate, enable constructor() trigger the event and get current orientationIsPort.
Binding orientationIsPort to html as:



<StackLayout *ngIf="orientationIsPort">
......
</StackLayout>


<StackLayout *ngIf="!orientationIsPort">
......
</StackLayout>


##Note:
The following file is not for aforesaid function, but for other function in other repo:
app.component.1...
app.component.max...
app.component.min...


#License:
MIT
