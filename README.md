# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## what I learnt so far

````
<button 
    type='button' 
    onClick={() => window.open(
      'https://github.com/HRegniez'
      )}>
      Github
</button>
```` React - Opens links in new tab

````
<input 
    type="url" 
    placeholder="Enter a URL" 
    value="" 
    onChange={()=>{}}
    required
    className="url_input peer"
  />
  <button
    type="submit"
    className="submit_btn peer-focus:border-gray-700 peer-focus:text-gray-700"
  >
    Submit
  </button>
```` Tailwin - When imput focused, the button will chnge wtyles with it
