# UpperConfidenceBound
# Algorithm comes under Reinforcement learning implemented on Ads_CTR_Optimisation dataset.
# The algorithm is implemented as follows:
# Step 1: Initialize the rounds n and we have ad i at every round. Consider two terms at every round and for each ad i
          # Ni(n): The number of times the ad i was selected upto round n.
          # Ri(n): Sum of rewards of ad i upto round n.
# Step 2: Compute average reward of each ad i upto round n as: ri(n) = Ri(n)/Ni(n) and compute delta_i(n) = sqrt(3/2*(log(n)/Ni(n)).
# Step 3: Finally, we select the ad i that has maximum Upper Confidence bound ri(n) + delta_i(n).
# Most commonly used algorithm in the fields of advertising and digital marketing.
