Website: https://zzzcode.ai/

## Do you want to contribute?

Awesome! Let us know your thoughts on this project and what you want us to improve. Also, let us know what you will add to our prompt template or anything else you want to discuss.

Keep in mind this project is in the ALPHA stage, so a lot of weekly improvements are being made. Including the code source, to be available to the public (there is not much to hide here, only a simple website using Chat GPT AI)

## How to embed a form in my website

To embed a form in your website, you need:

1. A form with the `action="https://zzzcode.ai/answer-question"` and `method="get"`
2. A visible or hidden input (or textarea) with the name "p1" for the question context: `<input name="p1" type="hidden" value="[Topic]">`
3. A visible textarea for the question with the name "p2"
4. A submit button

```html
<form action="https://zzzcode.ai/answer-question" method="get">
    <h2>Got any [Topic] Question?</h2>
    <br>
    <input name="p1" type="hidden" value="[Topic]">
    <div class="form-group">
        <label for="uiP2">Ask any [Topic] Questions and Get Instant Answers from ChatGPT AI:</label>
        <textarea id="uiP2" name="p2" type="text" class="form-control" placeholder="Ask any  [Topic] question..." rows="5"></textarea>
    </div>
    <button type="submit" class="btn btn-primary my-1">ChatGPT answer me!</button>
</form>
```

## Contribute

The best way to contribute is by **spreading the word** about the library:

 - Blog it
 - Comment it
 - Star it
 - Share it
 
A **HUGE THANKS** for your help.

## More Projects

- Projects:
   - [EntityFramework Extensions](https://entityframework-extensions.net/)
   - [Dapper Plus](https://dapper-plus.net/)
   - [C# Eval Expression](https://eval-expression.net/)
- Learn Websites
   - [Learn EF Core](https://www.learnentityframeworkcore.com/)
   - [Learn Dapper](https://www.learndapper.com/)
- Online Tools:
   - [.NET Fiddle](https://dotnetfiddle.net/)
   - [SQL Fiddle](https://sqlfiddle.com/)
   - [ZZZ Code AI](https://zzzcode.ai/)
- and much more!

To view all our free and paid projects, visit our website [ZZZ Projects](https://zzzprojects.com/).
