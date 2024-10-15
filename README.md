# Austerity_and_Bank_Lending
 Working Paper

This repository contains a working paper that investigates the effects of fiscal consolidation (austerity policy shocks) on commercial bank lending. The study utilizes IV state-dependent local projections to estimate the impact of narratively-identified fiscal consolidation policy shocks on various measures of bank lending.

The austerity policy shock data, spanning from 1978 to 2019, along with estimates of the size of these fiscal consolidations, are sourced from \cite{jorda_local_2024}, originally constructed and provided by Guajardo, Leigh, and Pescatori. The data used to measure bank lending behavior includes total loans, loans to households, loans to corporates, total mortgages, and loans-to-deposits, obtained from the 6th release of the Jordà-Schularick-Taylor Macrohistory dataset. Additionally, the cyclically-adjusted primary balance data is sourced from the OECD.

The methodology employed in this study follows the procedures outlined in \cite{jorda_time_2016}. Firstly, the austerity shock size variable is used as an instrument to estimate the treatment effect of dCAPB. Local projections are then utilized to estimate the multiplier effect of this treatment on different aggregate debt levels. More dependent variables will be added as the project progresses. The results are presented with 95 percent confidence bands and the joint test. The code used in this study is a replication of \cite{jorda_local_2024}. Data beyond 2007 is excluded to omit the effects of the global financial crisis in our analysis.

Initial results show that fiscal consolidation policies cause commerical banks to reduce real lending to the private sector (see prelim results pdf). The state-dependent IRFs display evidence that real lending to households and with real mortgage lending are negatively impacted by fiscal consolidation during a boom. The IRF results for real lending to businesses should be updated. With fixed code, it shows similar results to the real lending to households IRFs.

