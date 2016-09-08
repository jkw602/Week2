# Week2
Week 2 Lab COMP 230
$Counter = 0
$Die1 = 0
$Die2 = 0
$Score = 0
Write "This is a Dice Simulator"
While ($Score -ne 12)
{
$Counter += 1
$Die1 = $randomNo.Next(1,7)
$Die2 = $randomNo.Next(1,7)
$Score = $Die1 + $Die2
Write "Rolled a $Die1 and $Die2"
Write "Total was $Score"
}
Write "It took $Counter rolls to get a 12"
