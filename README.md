# hardware-blacklist

Various types of hardware that was keeping up with the production of other nodes and is no longer able to keep up is listed below. 

Note that all CPU's listed are no longer keeping up in single CPU motherboards. However AMD EPYC CPU's will work in Dual CPU motherboards nicely for the most part as even dual EPYC 7302's with a total of 32 cores  were working last year. However a minumum of 24 core EPYC CPU's is now recommended for Testnet. Possibly more are needed in Mainnet soon. This is only a prediction and cannot be tested or accurately forecast.
    
NO LONGER WORKING IN SINGLE CPU
    
    AMD CPU'S SLOWER THAN RYZEN 3700X (WILL NO LONGER WORK)
    AMD 3700X
    AMD 3900X (MARGINAL AS IT MAY BARELY WORK NOW)
    
WARNING: DO NOT USE 1U RACK CASES WITH HI FREQUENCY CPU'S LIKE 5950X. 

    Use only 2U or more with big fans on CPU cooler and big fans pulling air from front to back of rack case.
    
    You must adhire to electrical engineering best practices when applying electricity to any transistor and that means that the transistor must not operate past 50% of its capacity or anywhere near its maximum temperature range in order to allow the life of the transistor to not be prematurely shortened. This means that the CPU must be twice as fast as what you need for it to run in production speed. And this means that you must cool the CPU down to a midrange temperature for its recommended operating temperature range. However with a 4.6 GHz clock speed of the 5950X CPU, extreme heat of 200 Watts is emmitted at full turbo and full core utilization, and thus if the CPU temperature is seen to get over 60 or so degrees, the CPU governor shuts down the turbo and throttles back the cores clock speed which stops the server from keeping up with the rest of the Solana nodes. You then will falsely believe that your CPU is too slow when in fact it is not.
    
