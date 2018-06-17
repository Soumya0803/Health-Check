# Health-Check
Health check is the easiest way to provide doctors with up to date information about patient’s medical history. It consists of concise data on symptoms and prescribed medicines.
## setup
1. create database - 'health'
2. execute the following query:
> CREATE TABLE `main` (
 `name` varchar(20) NOT NULL,
 `age` int(4) NOT NULL,
 `gender` varchar(20) NOT NULL,
 `id` varchar(20) NOT NULL,
 PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1

3. table structure:
![alt text](main-table-structure.png "Logo Title Text 1")

4. run create_table.php (alternative to step 2) to create the table automatically 
