## Kimball architecture Vs Inmon Architecture

I'll  write this article in order to clarify the difference between Kimball architecture and Inmon architecture, as well as how to choose between them?


![image](https://user-images.githubusercontent.com/58523013/232320853-e3ff9ba1-0354-4e2c-9f5e-21cd1256a518.png)


### Kimball's architecture ( dimensional Modeling)

![image](https://user-images.githubusercontent.com/58523013/232321075-19afe81c-f5d2-4606-a304-3342d47370c6.png)

<br>

- Kimball Focus adds Business value throughout the enterprise, meaning that if an enterprise has a business for example sales, it has only create a data Mart to provide reporting and analytical capabilities for these Sales.

 - Kimball is suitable for organizations and enterprises which  have many changes: start-ups, small, medium companies, and companies want to go fast.
- Kimball works well in the agile and quick delivery for the business which means we don't need to create the whole infrastructure to get value  to user.

### desadvantages of kimball's pardigm

* Lose the idea of a single source of truth because the entire data warehouse isn't fully integrated.
* redundant data(dénormalization) added to the model because Kimball is based in a business so we can find a common data between two subjects .
* The model does not help strategic decision-making. As decision-making requires all informations and indicators for each department

### Inmon's architecture ( Enterprise Modeling)
![image](https://user-images.githubusercontent.com/58523013/232321542-e434e70d-4650-4616-b596-b703af0ecbbe.png)
