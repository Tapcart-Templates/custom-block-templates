
# Loox reviews block

## Description
The LOOX Reviews block allows you to display product reviews from your LOOX account on your Tapcart app. With this block, you can build customer trust by showcasing genuine and positive reviews from past customers.

## How this block works
The LOOX Reviews block displays product reviews from your LOOX account. It retrieves the reviews using your Shopify product ID and displays them in a clean and easy-to-read, carousel format.

1. Block uses your Shopify store handle + product ID to fetch the reviews.
2. From here, customers can read the reviews of the product

## Setup Instructions
> Reach out to your Tapcart rep if you have any questions while configuring this Custom Block

### 1. Create a new Custom Block
1. Start [here](https://app.tapcart.com/custom-blocks) to create a new Custom Block
2. Give it a name by clicking on 'Name your block'

### 2. Copy this template's HTML, CSS, and JS over to the Custom Block Editor
1. Copy the HTML from [index.html](https://github.com/Tapcart-Templates/custom-block-templates/edit/main/Loox%20Reviews/index.html) file in this folder, and paste it in the HTML tab in the editor
2. Copy the CSS from [styles.css](https://github.com/Tapcart-Templates/custom-block-templates/edit/main/Loox%20Reviews/styles.css) file in this folder, and paste it in the CSS tab in the editor
3. Copy the Javascript from [script.js](https://github.com/Tapcart-Templates/custom-block-templates/edit/main/Loox%20Reviews/scripts.js) file in this folder, and paste it in the JS tab in the editor

### 3. Make some code edits
The following lines of code in the custom block will need to be edited for the block to work as expected.

- **[REQUIRED]** Line 5 (JavaScript) replace "YOUR-STORE-HANDLE" with your store handle.  For example: for the store emmys-tapcart-boutique.myshopify.com, the store handle is `emmys-tapcart-boutique`

- To preview in the Code Editor, add a PRODUCT ID to the Variable Preview JSON To do this, enter the editor, select the 'Settings' tab, and use the text box to assign preview values. If a variable receives a value in this text box, the editor will automatically assign this value to the occurrence of the variable in the block preview.  See image below.

![Variable JSON object](../Loox%20Reviews%20-%20Carousel/assets/Screenshot%202023-05-18%20at%204.59.05%20PM.png)





