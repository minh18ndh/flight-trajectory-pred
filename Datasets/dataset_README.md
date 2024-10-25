
(1) dataset: original raw flight dataset

(2) dataset: drop 9 columns and all the rows contain 'null' callsign from (1)
   (2-3) csv file: all the callsigns represent helicopters

(3) dataset: drop 2 more columns, remove all the rows contain 'helicopter' callsign, 
            reduce sampling rate to half (2 seconds / 1 datapoint) from (2) using (2-3) in the process
   (3-4) csv file: all the 'time' values belong to segments shorter than 1 minute and longer than 30 minutes

(4) dataset: remove all the 'time' values belong to segments shorter than 1 minute and longer than 30 minutes 
            from (3) using (3-4) in the process

(5) dataset: extract all the data of flight record N86HD-abcd31 from (4)

(6) and (7) dataset: split from the (5) into training and testing subsets

You can view the datasets here: https://husteduvn-my.sharepoint.com/:f:/g/personal/minh_ndh210591_sis_hust_edu_vn/Eg2VgOwTFeFHn3h8m0TuXLEB9DpR3fSsS8KE71RzVTaOWg?e=SPccD2
