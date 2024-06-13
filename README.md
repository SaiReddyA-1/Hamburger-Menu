# Hamburger Menu App Implementation

In this project, I have completed the implementation of a **Hamburger Menu** app by applying the concepts learned so far.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-output-v0.gif" alt="hamburger menu output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-about-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home](https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-home-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - About](https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-about-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Menu](https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-popup-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-not-found-lg-output.png)

### Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

### Completion Instructions

The app has the following functionalities:

- Initially, the Home Route is displayed.
- When the hamburger icon button in the header is clicked, the popup opens.
  <div style="text-align: center;">
      <img src="https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-popup-img.png" alt="popup" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
  </div>
  <br/>
- When **Home** is clicked, the page navigates to the Home Route.
- When **About** is clicked, the page navigates to the About Route.
- When the close button is clicked, the popup closes.
- When the website logo in the Header is clicked, the page navigates to the Home Route.

### Components Structure

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-component-structure-breakdown-home.png" alt="component structure breakdown home" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/hamburger-menu-component-structure-breakdown-about.png" alt="component structure breakdown about" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Implementation Files

Use these files to complete the implementation:

- `src/App.js`
- `src/components/Header/index.js`
- `src/components/Header/index.css`
- `src/components/Home/index.js`
- `src/components/Home/index.css`
- `src/components/About/index.js`
- `src/components/About/index.css`
- `src/components/NotFound/index.js`
- `src/components/NotFound/index.css`

### Quick Tips

To build this project, take a look at the [React Popup](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=b01fca1c-aa5c-4d79-b81e-0220e7649bd0&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467) reading material

- To style popup content use `.popup-content` class

```jsx
<Popup
  modal
  trigger={
    //write code here
  }
  className="popup-content"
>
  //write code here
</Popup>
```

### Important Note

**The following instructions are required for the tests to pass**

- `Home` Route should consist of `/` in the URL path
- `About` Route should consist of `/about` in the URL path
- No need to use the `BrowserRouter` in `App.js` as it is already included in `index.js`
- The hamburger icon button should have the `data-testid` as **hamburgerIconButton**
- The close button in the popup should have the `data-testid` as **closeButton**
- `GiHamburgerMenu` from react-icons should be used for **Hamburger Icon** in the Header
- `IoMdClose` from react-icons should be used for **Close Icon** in the Popup
- `AiFillHome` from react-icons should be used for **Home Icon** in the Popup
- `BsInfoCircleFill` from react-icons should be used for **About Icon** in the Popup

### Resources

#### Image URLs

- [https://assets.ccbp.in/frontend/react-js/hamburger-menu-website-logo.png](https://assets.ccbp.in/frontend/react-js/hamburger-menu-website-logo.png) alt should be **website logo**
- [https://assets.ccbp.in/frontend/react-js/home-sm-img.png](https://assets.ccbp.in/frontend/react-js/home-sm-img.png) alt should be **home**
- [https://assets.ccbp.in/frontend/react-js/home-lg-img.png](https://assets.ccbp.in/frontend/react-js/home-lg-img.png) alt should be **home**
- [https://assets.ccbp.in/frontend/react-js/about-sm-img.png](https://assets.ccbp.in/frontend/react-js/about-sm-img.png) alt should be **about**
- [https://assets.ccbp.in/frontend/react-js/about-lg-img.png](https://assets.ccbp.in/frontend/react-js/about-lg-img.png) alt should be **about**
- [https://assets.ccbp.in/frontend/react-js/not-found-img.png](https://assets.ccbp.in/frontend/react-js/not-found-img.png) alt should be **not found**

#### Colors

<br/>
<div style="background-color: #dcdcdc; width: 150px; padding: 10px; color: black">Hex: #dcdcdc</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #616e7c; width: 150px; padding: 10px; color: black">Hex: #616e7c</div>

#### Font-families

- Roboto
