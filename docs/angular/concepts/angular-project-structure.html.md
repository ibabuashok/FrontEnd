
<p><span style="text-decoration: underline;"><strong>Angular Project Structure</strong></span></p>
<p><span style="text-decoration: underline;"><strong>Components:</strong></span></p>
<p><em>Components</em>&nbsp;are the basic building blocks. They display data, get user input and call service methods to get/send data.</p>
<p>Components define Views and use Services.</p>
<p>Component is generally created as set of three files: HTML + Typescript + CSS</p>
<p>For example, AppComponent is created as follows:</p>
<p>app.component.ts&mdash; the component class code, written in TypeScript.</p>
<p>app.component.html&mdash; the component template, written in HTML.</p>
<p>app.component.css&mdash; the component's private CSS styles.</p>

<p><span style="text-decoration: underline;"><strong>Key Files:</strong></span></p>
<li>..\src\index.html is the default page.&nbsp;</li>
<li>..\src\app\ contains all the angular components&nbsp;</li>
<li>..\package.json contains all the information about project dependencies and their versions</li>

<p><span style="text-decoration: underline;"><strong>NgModules:</strong></span></p>
<p>An angular application is defined by a set of NgModules</p>
<p>NgModules collect related code into functional sets;</p>
<p>NgModules provide a compilation context for components.</p>
<p>An app always has at least a root module (conventionally named AppModule and defined in a file named app.module.ts) that enables bootstrapping, and typically has many more functional modules. </p>
<p>NgModules can import functionality from other NgModules, and allow their own functionality to be exported and used by other NgModules. For example, to use the router service in your app, you import the Router NgModule.</p>
<p>Organizing your code into distinct functional modules helps in managing development of complex applications, and in designing for reusability. In addition, this technique lets you take advantage of lazy-loading—that is, loading modules on demand—to minimize the amount of code that needs to be loaded at startup.</p>
<p>An NgModule is defined by a class decorated with @NgModule()</p>
<p>A root NgModule always has a root component or an entryComponent that Angular creates and inserts into the index.html host web page during bootstrapping.</p>
<p>The components that belong to an NgModule share a compilation context.</p>
<p>All Angular libraries are NgModules, such as FormsModule, HttpClientModule, and RouterModule.</p>
<p>Modules can also add services to the application.</p>
<p>Modules can be loaded eagerly when the application starts or lazy loaded asynchronously by the router.</p>


While you can put more than one component tree on a host web page, most applications have only one component tree and bootstrap a single root component.

<a href="https://github.com/ibabuashok/FrontEnd/tree/master/src/angular/tutorial/angular-getting-started/my-app/src/app" target="_blank">Source Code</a>

<a href="../../">Home</a>
