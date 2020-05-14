```

library(caret)

kfold = 10 ## number of folds
n = 100 ## number of samples
folds <- createFolds(y = 1:n, k = kfold)

lossInfo <- sapply(1:kfold, function(z){
  train = data[-folds[[z]], ]
  test = data[folds[[z]], ]
  parInfo = YourMethod(data = train, ...)
  LossFun(parInfo, data = test)
})

modelLoss = sum(lossInfo)

## Model Assessment
modelSet = c(Model1, Model2, Model3, ...)
n_model = length(modelSet)

sapply(1:n_model, function(x){
  sum(sapply(1:kfold, function(z){
    train = data[-folds[[z]], ]
    test = data[folds[[z]], ]
    parInfo = YourMethod(data = train, ...)
    LossFun(parInfo, data = test)
  }))
})

```
