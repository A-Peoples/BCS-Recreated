# BCS-Recreated
I attempted to recreate the Bowl Championship Series in Google Colab.

Explanation: https://medium.com/@ahlon.aj.peoples/recreating-the-bowl-championship-series-bcs-cd2073f6c7e5

#BCS 1.1 Update
  - changed list of every team into .unique()
  - edited formula to be more precise ((wins + c_wins) - (losses + c_losses) * 10) + (eilo * 0.1)) * 0.1
  - rounded to the ten thousands place
