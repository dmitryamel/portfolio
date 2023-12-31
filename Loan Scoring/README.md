# Описание
Необходимо построить скоринговую модель, которая позволит максимизировать совокупную экономическую прибыль (в процентах от суммы выдачи). Скоринговая модель получает на вход значения факторов, на выходе выдает ответ, нужно ли выдавать данный заем.

Значение экономической прибыли считается следующим образом:

- Loss = Unpaid * (EL, expected loss)  
- InvestorProfit = Earned — Loss  
- Profit = InvestorProfit + Commission  
- Profit% = Profit / LoanIssued  

Задача модели состоит в том, чтобы выдавать на основе факторов займы таким образом, чтобы % экономической прибыли был максимальным.

**В качестве ответа необходимо:**
- написать скрипт, решающий данную задачу
- подробно описать ход решения
- предложить интерпретацию решения — какие именно факторы нужно изменить и почему