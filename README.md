```
useage:
   $0 <directory> [<from>] [<to>]

where
   <directory>: a directory relative to current working dir with gc files of the form gc.log.2013-02-21-13:01:21
                where the date is the start time of the jvm.
   <from>     : Start date of the plot in the form yyyy-mm-dd. Defaults to a week ago.
   <to>       : Stop date of the plot (non inclusivie). Defaults to tomorrow.
```



prequisites


Perl-mdules:
```
sudo cpan DateTime
sudo cpan install List::MoreUtils
sudo cpan install Params::Util
```

And gnuplot to make the pictures:
```
sudo port install gnuplot
```
