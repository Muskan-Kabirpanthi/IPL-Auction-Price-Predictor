# IPL-Auction-Price-Predictor
AuctionPrice Prediction-

    Multiple Linear Regression

    yi =β0+β1x i1+β2x i2 +...+βp x ip+ϵ

    Libraries

        1.numpy for arrays

        2.matplotlib.pyplot for visualization

        3.pandas

        4.seaborn for Statistical graphocs Visualization
        
        5.statsmodel for statistics modelling

    Multi-collinearity

    Rx = R-squared value of this model

    VIF = 1/1-Rx^2

    HeatMap corr
    Screenshot 2020-08-13 at 6 10 41 PM

    Here, 1.T-RUNS and ODI-RUNS are highly Correlated.

      2.ODI-WKTS and T-WKTS are highly Correlated.
      
      3.Batsman Features - RUNS-S,HS,AVE,SIXERS are highly Correlated.
      
      4.Bowler's Features - AVE-BL ,ECON and SR-BL are highly Correlated.

    R- Squared value 0.75 Training Dataset .

    R- Squared value 0.44 validation Dataset .
