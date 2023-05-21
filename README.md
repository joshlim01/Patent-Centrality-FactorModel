# Patent-Centrality-FactorModel

Using CRSP data from WRDS and Global Corporate Patent Dataset from UVA Darden. We consider a new factor called "Patent Intensity", which is the number of issued patents divided by market capitalization. 
We also consider anothe factor called "Centrality", which is the node centrality of a given asset with respect to other assets. We incorporate these factors into the Fama-French 5 factor model to create
a 7 factor model. 

Below would be a sample of a node centrality output.

![Map](https://github.com/WilliamClintC/Patent-Centrality-FactorModel/assets/118032486/595b58d2-7827-4231-96c2-94fee857d100)

The main code FactorModelV5.ipnyb contains the 7 factor model, along with the estimated returns and comparison visualization of model to actual returns. 
<img width="476" alt="Screenshot 2023-05-21 145517" src="https://github.com/WilliamClintC/Patent-Centrality-FactorModel/assets/118032486/2b54d6e8-6788-4f57-a228-a21a9ad0937b">

<img width="286" alt="Screenshot 2023-05-21 145607" src="https://github.com/WilliamClintC/Patent-Centrality-FactorModel/assets/118032486/f0d3392e-8a00-4691-aeb9-be363a8be953">
![output](https://github.com/WilliamClintC/Patent-Centrality-FactorModel/assets/118032486/2f6c27f3-40b8-46b1-90fd-06dfa7ffe3de)
