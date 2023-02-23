# Bootstrap

* `style:b5` to grab Bootstrap CDN

* responsive meta tag:

`<meta name="viewport" content="width=device-width, initial-scale=1">`

* Pay very close attention to proper nesting. Rows should never be siblings to containers, columns never siblings to rows.

* `col-6 m-auto` is a good way to center and adjust margins accordingly without using flexbox.

* Content only belongs in the columns, not in the containers or the rows.

* Layout content before you start filling everything in. To get a good idea of where everything is, add this into head tag:

`<style>
    * {
      border: 1px red dashed
    }
    .row div{
      height: 100px;
    }
  </style>`

  * For placeholder images:

  `//placehold.it/200x200`

  * This will give an image 200px x 200px