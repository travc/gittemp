gittemp
=======

Misc temp stuff

Command to run CollectWgsMetrics on each chromosome of the reference ref.fa:  
```parallel --gnu --colsep '\t' -a ref.fa.fai java -Xmx4g -jar CollectWgsMetrics.jar INPUT=in.bam REFERENCE_SEQUENCE=ref.fa  OUTPUT="WGS_{1}.out" INTERVAL_LIST_STRING="{1}"```
