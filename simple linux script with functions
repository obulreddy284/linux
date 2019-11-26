
get_db_size () {
	 ## if file is not empty
        if [ -s /path to a file .txt/.csv/.json  ]  
                then
                echo $(date|awk '{print $2$3}'|tr '\n' ',' && du -h /a path | grep -w -e 'x\.db' -w -e 'lacir\.db' -w -e 'y\.db' -w -e 'z\.db' | awk '{ORS=","}{print $1$2}'|sed 's/,//4') >> /some_path_to_write_to.csv
         ## if file is empty
	else                                            
                echo date,x,y,z >/some_path_to_write_to.csv
                get_db_size
        fi
}
 ## if file exists
if [ -e /path to a file .txt/.csv/.json ] 		
then
	get_db_size
  ## if file doesn't exist
else
	touch /path to a file .txt/.csv/.json
	get_db_size
fi
