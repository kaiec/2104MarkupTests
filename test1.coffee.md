Github Markup Tests
===================


    console.log("Start")
    hello = ->
        console.log("In Hello")

    for i in [1..10]
        console.log("Not indented automatically")

    world = (what) ->
        console.log("Hello #{what}")



''''
console.log("Start")
hello = ->
    console.log("In Hello")

for i in [1..10]
    console.log("Not indented automatically")

world = (what) ->
    console.log("Hello #{what}")

''''

And now we continue [here](coolLib.coffee.md).