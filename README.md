Promote this utility
#cesDataParse
    1. Accept configuration parameters (arg list)
    2. Dynamic parser of structured lines (no line continuations; that's an issue)
    3. Parser creates clusters that be 'viewed' from any node (name in this case)
    4. Clusters use ANN-like metrics to for fast ordering of nodes. Numeric values can represent distance.
###Anomaly finding
    1. Not sure how this works. Its not just aggregate counts vs contributors. ??
    
###Reporting
    1. Reporters: csv/tld/xml/json
    2. Layout static text
    3. Comments: tracking origins of report entity
    
###Entity Capture
    1. If parameters allow, (explicitly), should capture entity identifiers (names and name variants)
    2. Persist into some portable format.



Command line tool to parse San Francisco election data. Example usage:

    ./sfbparse.rb ~/Downloads/Mayor

Output is numerous lines which look like this:

> DAVID CHIU is preferred to ED LEE by 36896 voter(s).
