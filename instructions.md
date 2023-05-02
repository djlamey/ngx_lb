@lab.EssayTextBox(test)[50]
===
<style>
span.coolfont{
    font-family: Oswald;
}

</style>
# Customizing Instructions: IDL-MD Syntax

Select the language you would like to perform the lab in: @lab.DropDownList(language)[English,Spanish]

!INSTRUCTIONS[Favorite Food Intro](https://raw.githubusercontent.com/LODSContent/lod-training/master/favorite-food/intro.md)

:::

<span class=coolfont> Login to the VM using the following information:

:::creds

|Key|Value|
|--|--|
|Username|+++@lab.VirtualMachine(LODTraining).Username+++|
|Password|+++@lab.VirtualMachine(LODTraining).Password+++|

[Check out our Slack Community!](http://labauthor.slack.com/ "LODS Slack Community")

^INSTRUCTIONS[Click to View Code][bash-code]

>[bash-code]:
>```Bash-notab-nocolor-linenums
>echo "My favorite 
>    food is:
>        @lab.Variable(food)" >> C:\Users\LabUser\Desktop\MyFavFood.txt
>```

In the box below, type the name of your favorite food:  
@lab.TextBox(food)

@lab.Activity(favfood)

Select the food you would like to learn more about: @lab.DropDownList(option)[None,Salad,Chicken]

:::salad(option=salad)

Salad is a mixtue of small pieces of food.

:::

:::chicken(option=chicken)

Chicken is the most common type of poultry

:::

!INSTRUCTIONS[Selected Food](https://raw.githubusercontent.com/LODSContent/lod-training/master/favorite-food/None.md)

<details>
<summary>Food Examples</summary>

<details>

 <summary>Fruits</summary>

 - Apples

 - Bananas

 </details>



<details>

 <summary>Vegetables</summary>

 - Brocolli

 - Carrots

 </details>

</details>

1. [] did you check the box

1. [] second box to +++check+++

!IMAGE[Screenshot](screens/cj33yrzp.jpg)

!IMAGE[Screenshot](screens/kxzhf5aw.jpg)

@lab.Activity(Question1)

@lab.ActivityGroup(Group1)

Here are the changes
===

#Testing
<p>
	<code class="execute" title="Run command">
		CREATE KEYSPACE demo WITH replication = {'class': 
		'SimpleStrategy', 'replication_factor': 1};"
		::after
	</code>
</p>
