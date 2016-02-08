# Exceptions: The failwith Function (F#)

The **failwith** function generates an F# exception.


## Syntax


```


failwith error-message-string

```



## Remarks
The *error-message-string* in the previous syntax is a literal string or a value of type **string**. It becomes the **Message** property of the exception.

The exception that is generated by **failwith** is a **Microsoft.FSharp.Core.FailureException** exception, which is a reference that has the name **Failure** in F# code. The following code illustrates the use of **failwith** to throw an exception.

[!code-fsharp[Main](snippets/fslangref2/snippet6001.fs)]
    
## See Also
[Exception Handling &#40;F&#35;&#41;](Exception-Handling-%28FSharp%29.md)

[Exception Types &#40;F&#35;&#41;](Exception-Types-%28FSharp%29.md)

[Exceptions: The try...with Expression &#40;F&#35;&#41;](Exceptions-The-try...with-Expression-%28FSharp%29.md)

[Exceptions: The try...finally Expression &#40;F&#35;&#41;](Exceptions-The-try...finally-Expression-%28FSharp%29.md)

[Exceptions: the raise Function &#40;F&#35;&#41;](Exceptions-the-raise-Function-%28FSharp%29.md)
