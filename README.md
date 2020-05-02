# Sequential_File_Structure_Simulator 
<strong>(순차 파일 구조 시뮬레이터)</strong>

- A sequential file is the most basic method of organizing records. It is a method of sequentially storing records in sequence when creating a file.

- In this type of sequential file structure, if you want to Add new record, Delete existing record, or Correct existing data in the master file, you must use batch processing.

- Batch processing creates a transaction file of what you want to do with an existing master file (add a new record, delete an existing record, modify an existing record), and processes the existing master file and transaction file according to the key value (data value of a record that can be sorted) and the action you want to perform (Insert, Delete, Correct) when you renew the new master file.

- This Sequential FIle Structure Simulator is a program that simulates key sequential files and functions are shown in the following table


<strong>< Sequential File Structure Simulator Functions List ></strong>

|---|:---:|
| (1) | Error detection and output of input data through editing |
| (2) | Outputs student information master file (before and after renewal) |
| (3) | Update student information master file via transaction file (add, delete, modify) |
| (4) | Configuring and printing transaction files for updates |
| (5) | Output error logs during editing and transaction error logs during master file renewal |

<br></br>

<strong>< Normal Mode (with not use Any Mapping Method) Command List ></strong>
  
| Command | Action |
|---|:---:|
| init x or i x | Create x MB Storage File |
| read PSN or r PSN | Read data at Physical Sector Num(PSN) Position |
| write PSN data or w PSN data | Write data at Physical Sector Num(PSN) Position |
| erase PBN or e PBN | Erase data at Physical Block Num(PBN) Position |
| change | Change Mapping Method |

<br></br>


- Simulator that creates flash memory, reads data in physical sectors, inputs data, and erases data in blocks
- No limit on FlashMem Storage File creation capacity<br>

<br></br>

