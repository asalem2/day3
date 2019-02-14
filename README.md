Blog: https://medium.com/coding-crackerjack/spring-boot-and-reactjs-a50367d56521
Github:

Personal Notes:

-This is a react.js and Spring MVC back-end. 
-Start by creating the expense document in java.
-We will start from the bottom up.
```
package com.expenseManager.ExpenseManagerAPI.domain;

import org.springframework.data.annotation.Id;
import org.springframework.data.mongodb.core.mapping.Document;

@Document
public class Expense {

	@Id
	String id;
	String description;
	Integer amount;
	String month;
	int year;
	
	public String getId() {
		return id;
	}
	public void setId(String id) {
		this.id = id;
	}
	public String getDescription() {
		return description;
	}
	public void setDescription(String description) {
		this.description = description;
	}
	public Integer getAmount() {
		return amount;
	}
	public void setAmount(Integer amount) {
		this.amount = amount;
	}
	public String getMonth() {
		return month;
	}
	public void setMonth(String month) {
		this.month = month;
	}
	public int getYear() {
		return year;
	}
	public void setYear(int year) {
		this.year = year;
	}

}
```

The remaining of the code required me to close read detailed information.

