# React redux content fetch test
This is a simple test to check if you can work with react components, redux states and fetching content
The objective is to include a simple modal, call that modal using a button, and finnaly change the contents of the modal using a async action

What you will need:
* antd as the library
    * Modal component: https://4x.ant.design/components/modal/
    * Button component: https://4x.ant.design/components/button/

* Mockoon to mock an api endpoint: https://mockoon.com/
    * Set mockoon port to 3001, as the default 3000 will be used by this app

Steps:
* Make the modal appear using the "Open info modal" button
    * This should be done by dispatching an action to change the modalOpen state

* Change the contents of the modal when clicking the "Change info" button
    * This should be done by dispatching a async action that fetches the info from the api and updates the modalTitle and modalDescription states