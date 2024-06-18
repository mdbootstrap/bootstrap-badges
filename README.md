# Free Bootstrap Badges Component

Responsive Badges built with the latest Bootstrap 5. Badges add extra information like count or label to any content. Use counters, icons, or labels. Many examples and easy tutorial.

<p><strong>How to use it?</strong></p>
<p class="mb-2">
<strong>1. </strong>Download<a target="_blank" href="https://mdbootstrap.com/docs/standard/"> MDB 5 - free UI KIT</a></p>
<p class="mb-2"><strong>2. </strong>Choose your favourite customized example and click <code>show code</code> to see the code</p>
<p class="mb-3"><strong>3. </strong>Copy & paste the code into your MDB project</p>

--------------------

[📄 **Documentation & usage guide**](https://mdbootstrap.com/docs/standard/components/badges/)

These components were built with a **free Material Design UI Kit for the latest Bootstrap 5**.

<img height="25" src="https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-r.png">  [![GitHub Stars](https://img.shields.io/github/stars/mdbootstrap/mdb-ui-kit?label=Star%20now&style=social)](https://github.com/mdbootstrap/mdb-ui-kit/)

---------------------

 <h2 class="mb-4">Basic example</h2> 
 
```html

<h2>Example heading <span class="badge badge-primary">New</span></h2>

```

 
 <hr class="my-5">
 
 <h2 class="mb-4">Sizes
</h2> 
 
```html
<h1>Example heading <span class="badge badge-primary">New</span></h1>
<h2>Example heading <span class="badge badge-primary">New</span></h2>
<h3>Example heading <span class="badge badge-primary">New</span></h3>
<h4>Example heading <span class="badge badge-primary">New</span></h4>
<h5>Example heading <span class="badge badge-primary">New</span></h5>
<h6>Example heading <span class="badge badge-primary">New</span></h6>
```

 <hr class="my-5">
 
 <h2 class="mb-4">Button</h2> 
 
```html
<button type="button" class="btn btn-primary" data-mdb-ripple-init >
  Notifications<span class="badge badge-danger ms-2">8</span>
</button>
```

```html
<button type="button" class="btn btn-primary" data-mdb-ripple-init >
  Profile <span class="badge badge-danger ms-2">9</span>
  <span class="visually-hidden">unread messages</span>
</button>
```

 <hr class="my-5">
 <h2 class="mb-4">Colors
</h2> 
 
```html
<span class="badge badge-primary">Primary</span>
<span class="badge badge-secondary">Secondary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-danger">Danger</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-info">Info</span>
<span class="badge badge-light">Light</span>
<span class="badge badge-dark">Dark</span>
```
 <hr class="my-5">
 <h2 class="mb-4">Pills

</h2> 
 
```html
<span class="badge rounded-pill badge-primary">Primary</span>
<span class="badge rounded-pill badge-secondary">Secondary</span>
<span class="badge rounded-pill badge-success">Success</span>
<span class="badge rounded-pill badge-danger">Danger</span>
<span class="badge rounded-pill badge-warning">Warning</span>
<span class="badge rounded-pill badge-info">Info</span>
<span class="badge rounded-pill badge-light">Light</span>
<span class="badge rounded-pill badge-dark">Dark</span>
```

 <hr class="my-5">
 <h2 class="mb-4">Positioned

</h2> 
 
```html
<button type="button" class="btn btn-primary position-relative">
  Inbox
  <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill badge-danger">
    99+
    <span class="visually-hidden">unread messages</span>
  </span>
</button>
```
```html
<button type="button" class="btn btn-primary position-relative">
  Profile
  <span class="position-absolute top-0 start-100 translate-middle p-2 bg-danger border border-light rounded-circle">
    <span class="visually-hidden">New alerts</span>
  </span>
</button>
```

 <hr class="my-5">
 <h2 class="mb-4">With avatar

</h2> 
 
```html
<div class="d-inline-flex position-relative">
  <span class="position-absolute top-0 start-100 translate-middle p-1 bg-danger border border-light rounded-circle">
    <span class="visually-hidden">New alerts</span>
  </span>
  <img class="rounded-4 shadow-4" src="https://mdbootstrap.com/img/Photos/Avatars/man2.jpg" alt="Avatar" style="width: 50px; height: 50px;">
</div>
```

 <hr class="my-5">
 <h2 class="mb-4">Icon notifications
</h2> 
 
```html
<a href="">
  <i class="fas fa-envelope fa-lg"></i>
  <span class="badge bg-danger badge-dot"></span>
</a>

<a href="">
  <i class="fas fa-envelope fa-lg"></i>
  <span class="badge rounded-pill badge-notification bg-danger">1</span>
</a>

<a href="">
  <i class="fas fa-envelope fa-lg"></i>
  <span class="badge rounded-pill badge-notification bg-danger">999+</span>
</a>
```

 <hr class="my-5">
 <h2 class="mb-4">Icon inside


</h2> 
 
```html
<div class="badge badge-primary p-3 rounded-4">
  <i class="fas fa-chart-pie"></i>
</div>
```
```html
<section class="mb-5">
  <div class="row gx-lg-5">
    <div class="col-lg-6 mb-5">
      <div class="d-flex align-items-start">
        <div class="flex-shrink-0">
          <div class="p-3 badge-primary rounded-4">
            <i class="fas fa-cloud-upload-alt fa-lg text-primary fa-fw"></i>
          </div>
        </div>
        <div class="flex-grow-1 ms-4">
          <p class="fw-bold mb-1">Tutorials</p>
          <p class="text-muted mb-1">
            Dozens of free tutorials to help you discover the full potential of MDB.
          </p>
          <small><a href="">Learn more</a></small>
        </div>
      </div>
    </div>

    <div class="col-lg-6 mb-5">
      <div class="d-flex align-items-start">
        <div class="flex-shrink-0">
          <div class="p-3 badge-primary rounded-4">
            <i class="fas fa-database fa-lg text-primary fa-fw"></i>
          </div>
        </div>
        <div class="flex-grow-1 ms-4">
          <p class="fw-bold mb-1">Integrations</p>
          <p class="text-muted mb-1">
            MDB is integrated with all major technologies and tools.
          </p>
          <small><a href="">Learn more</a></small>
        </div>
      </div>
    </div>

    <div class="col-lg-6 mb-5">
      <div class="d-flex align-items-start">
        <div class="flex-shrink-0">
          <div class="p-3 badge-primary rounded-4">
            <i class="fas fa-stream fa-lg text-primary fa-fw"></i>
          </div>
        </div>
        <div class="flex-grow-1 ms-4">
          <p class="fw-bold mb-1">Backend friendly</p>
          <p class="text-muted mb-1">
            MDB is designed to be seamlessly integrated and used with the backend.
          </p>
          <small><a href="">Learn more</a></small>
        </div>
      </div>
    </div>

    <div class="col-lg-6 mb-5">
      <div class="d-flex align-items-start">
        <div class="flex-shrink-0">
          <div class="p-3 badge-primary rounded-4">
            <i class="fas fa-copy fa-lg text-primary fa-fw"></i>
          </div>
        </div>
        <div class="flex-grow-1 ms-4">
          <p class="fw-bold mb-1">Support and community</p>
          <p class="text-muted mb-1">
            The MDB team and our global community are there to support you.
          </p>
          <small><a href="">Learn more</a></small>
        </div>
      </div>
    </div>

  </div>
</section>
```
