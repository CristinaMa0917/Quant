### shock & trend
> This project works on recognizing oscillation or tendency during the changing stocks prices. It helps the stocker manager to decide when to sale or buy in stocks market.

- Burg algorithm is applied here to derive PSD according to normalized frequency. High PSD means that it is very possible that the market is suffering the shock. And it's not a good time to apply LSTM strategy. This method is verified with different stocks in variable time scale (day line or minute line). 


- Trade points are classified with defined rules which are realized in _'wave_divide.ipynb'_. And the prediction by Burg method in different way is showed in _'methodCompare.ipynb'_. Accuracy of this method is calculated in _'accuracyCheck.py'_ ,and the final result is __70%__ based on the tagged trade-points in _'wave_divide.ipynb'_. In the picture of 'rightDividedPoints.png', we can see the predicted shock points are catenated like a wave. 
