# Project description

I'm an analyst at a big online store. Together with the marketing department, I've compiled a list of hypotheses that may help boost revenue. I must prioritize these hypotheses, launch an A/B test, and analyze the results.

**I have:
- nine hypotheses on boosting an online store's
- file with orders
- file with the number of visits divided into group

**I'm going to do the following:
- prioritizing hypotheses using ICE and RICE frameworks
- studying cumulative revenue, average order size, and the relative difference in cumulative average order size for groups
- studying conversion rate
- studying anomalies
- find the statistical significance of the difference in conversion between the groups
- find the statistical significance of the difference in average order size between the groups
- find the statistical significance of the difference in conversion between the groups without anomalies
- find the statistical significance of the difference in average order size between the groups without anomalies
- make conclusion


# at first, Loading all the libraries
from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = 'all'

import pandas as pd
import numpy as np
#!pip install sidetable
import sidetable as stb
import scipy.stats as st
from datetime import datetime
import matplotlib.pyplot as plt
from matplotlib.pyplot import figure
import seaborn as sns
