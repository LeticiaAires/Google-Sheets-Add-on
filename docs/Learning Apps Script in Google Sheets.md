# Learning Apps Script in Google Sheets

Main pointers in the journey of developing Google Sheets Add-on

1. If you type sheets.new on your browser, you go directly to a blank sheet on google sheets (pretty cool if you ask me)
2. Apps Script is just like JavaScript.
```
  function CPM(cost, views) {
    const cpm = cost / (views / 1000)
    return cpm
  }
```
3. You can make GS recognize you custom function as a native you, enabling it's autocomplete properties.
 ```
   /**
   * Calculate Cost per Mille (CPM)
   * @param {cost} cost - input cost
   * @param {views} views - input views
   * @customfunction
   */
 ```
4. When naming a custom function, there are a lot of little details you must keep in mind. I don't remember any of them:)
5. OAuth Consent Scren
   - External;
   - Add Authorized Domain;
   - Add Developer Contact Info;
6. When you find this Oauth Scopes, you must reasearch what you project needs and then manually add stuff like this:
   https://www.googleapis.com/auth/script.container.ui
   https://www.googleapis.com/auth/spreadsheets.currentonly
7. 
