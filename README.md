# Music_Power_Bi
I recreated my sql project in Power Bi by adjusting relationships between tables, writing DAX functions and creating visuals.


# Checking values and missing Values

I check missing values, dublicates and errors in power Querry.

![image](https://github.com/user-attachments/assets/c96fab15-96f0-4309-834d-51c67fa0e46e)


I started  star schema between tables.

![image](https://github.com/user-attachments/assets/969640f1-74cd-46fb-8995-7ceb91db437c)

I started my reporting by defning my KPI's thats why i put total revenue, amount of shopping and Amount of customer.
And it is important to know this metrics.

![image](https://github.com/user-attachments/assets/2f6341f4-07c7-44c3-af41-7eb4a4e922d1)

I get total value from total in invoice table,amount of shopping by invoice_line and total customer from invoice.
I take customer id from invoice line instead of customer table because it is much more updated.

First of all, i wanted answer 'What is the Top 5 country in terms of Total Revenue" question by tree map.

![image](https://github.com/user-attachments/assets/8b7abc1f-d2ca-4340-aa27-6aa0c8dcb97a)

Then i decided to show distribution of genres that answer "What is the distribution of Genres?" question so i created donut chart.

![image](https://github.com/user-attachments/assets/be66a8f9-7b76-497f-a0e3-a93f8dae4478)

Next, i added two slicers to show changes by genre and Date.In genre slicer, i use vertical.In date slicer, i prefferred dropdown because of it is much more functional.

![image](https://github.com/user-attachments/assets/33132b8b-5af9-4347-a0c4-071737b910c6)

To interact with other graphs, i made new columns using RELATED dax to connect Genre table in invoice_line.
So i use many id to reach genre name.And to update revenue by genre with using invoice_line, i made relation in both ways.
I make connection both way in track and genre tables.

![image](https://github.com/user-attachments/assets/4f541880-456d-4cb3-a2cd-7f7ab32c13f5)

![image](https://github.com/user-attachments/assets/8c4b968b-76b3-4b5a-a228-ef2ce668a7b6)

Later on,i created line and stacked column.In line, i wanted to show average revenue. In the stack,i used Total revenue.
So i can answer "Most Saled Cities?"  question.

![image](https://github.com/user-attachments/assets/1d603ae5-ff7f-4a24-a2a5-0ea3e4f483b4)


Then, i wanted to observe changes by Years and Months thats why i use waterfall graph. i use date from invoice table.

![image](https://github.com/user-attachments/assets/6534cc8d-7a82-4234-8206-8e443f715f01)

In the end, i wanted to answer "Who made the most purchase?" question.So i created a table to show by N filter.

![image](https://github.com/user-attachments/assets/808512e5-c605-414a-9119-1af8727d01cb)

![image](https://github.com/user-attachments/assets/b3d19d8b-bdc0-4f99-8177-3e9c4405da9a)

Also, i wanted to add image and Text to complete my Dashboard.

![image](https://github.com/user-attachments/assets/8205bed7-bcab-419e-985b-af0d4aa88ce1)

I finished all off the graph but i can not still answer all questions and i do not wanted to design new dashboard because there are only 3-4 questions.
So i decided to create pop up window.In next page, i created mini dashboard.

![image](https://github.com/user-attachments/assets/4b0859b9-c072-48cb-bafa-809a9fe75498)

