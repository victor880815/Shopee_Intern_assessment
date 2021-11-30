# Shopee_Intern_assessment
利用Flask建立一個查詢文章的API。 這個API的參數有：

q: 可以給定要查詢的字 (可為多個)
n: 回應幾篇文章
w: 每篇文章回應的字數
比如說: https://0.0.0.0:5000/shopee?q=檸檬&n=10&w=50 就會回傳標題或是內文有含"檸檬"的文章中，選最多10篇文章，每一篇文章回傳最初的50個字
