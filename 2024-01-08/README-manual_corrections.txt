The automated calculation for total tokens owed / LP is off by around 10-30% in our report output, due to us reading in the poolTVL (including Gamma Strategies' fees) rather than the user TVL. 

This oversight has been corrected in our latest codebase, and pushed to github. 

Reports moving forward will reflect the correct TVL & Rewards data as normal.