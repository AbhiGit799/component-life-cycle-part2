# component-life-cycle-part2

Hi, <br/>

This is a simple Angular POC created by Abhishek Choubey. <br/>

In this POC I tried to demonstrate Component Life Cycle, ng-content & Content Projection In Angular <br/>

In Angular we have 8 Lifecycle hook. Out of which  Here, I used <br/>

ngAfterContentInit() <br/>
ngAfterContentChecked() <br/>
ngAfterViewInit() <br/>
ngAfterViewChecked()<br/>

<b> Other Topics Covered </b> <br/>
@ContentChild  <br/>
ng-content <br/>

<br/>

<b> Components  Created  </b> <br/>
ng g c child
ng g c parent
ng g c mainoffice
ng g c suboffice
ng g c student

<br>
<b>Description:- </b>

In parent and child component I used content projection, @ContentChild, ngAfterContentInit(), and   ngAfterContentChecked().
<app-parent>
  <app-child></app-child>
</app-parent>

<br/>

In mainoffice and suboffice component I used @ViewChild, ngAfterContentInit(), ngAfterViewInit(), ngAfterViewChecked() <br/>
Here, In student component I used <ng-content></ng-content> for content projection. <br/>

<b> Note </b> <br> 
Content project = passing button /style/html from parent to child. <br>



Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>

Check my work 👉👉👉👉 https://abhigit799.github.io/component-life-cycle-part2/

<br/>
