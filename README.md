# wave-polymer-components

A Polymer component for the Wave ecosystem.

Includes:

* Business switcher dropdown
* Notifications shade


## Business Switcher

### How to use

1. Include the Polymer `platform.js`:

  ```
  <script src="../bower_components/platform/platform.js"></script>
  ```

2. Import the `business-list` element:

  ```
  <link rel="import" href="components/business-list.html">
  ```
  
3. Use it by passing in the currently active business (for the given page):

  ```
  <business-list active="<BUSINESS_ID_GOES_HERE>"></business-list>
  ```

4. You will get a business switcher like in the screenshot below.

#### `active`

* Mandatory
* This is the UUID for the currently active business. The business company name is display to the user at all times.

#### `position`

* Optional
* Supports either `left` or `right`
* Controls the position of the dropdown.


### Screenshot

![example](https://raw.githubusercontent.com/NickPresta/wbs-polymer-component/master/switcher.png)
