1. What was the bug?

The bug is the num1 and num2 are being concatenated as strings due to them being read as strings, not numbers.

2. How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use) and add it to your expand/screenshots directory.

In order to fix this, num1 and num2 will be converted into numbers so they can be added, using Number(). Screenshot is in expose/screenshots