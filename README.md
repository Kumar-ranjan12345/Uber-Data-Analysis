# Uber-Data-Analysis
This is a basic  exploratory data analysis and data visualization of uber dataset .

## Here is the dataset:
START_DATE*,END_DATE*,CATEGORY*,START*,STOP*,MILES*,PURPOSE*
1/1/2016 21:11,1/1/2016 21:17,Business,Fort Pierce,Fort Pierce,5.1,Meal/Entertain
1/2/2016 1:25,1/2/2016 1:37,Business,Fort Pierce,Fort Pierce,5,
1/2/2016 20:25,1/2/2016 20:38,Business,Fort Pierce,Fort Pierce,4.8,Errand/Supplies
1/5/2016 17:31,1/5/2016 17:45,Business,Fort Pierce,Fort Pierce,4.7,Meeting
1/6/2016 14:42,1/6/2016 15:49,Business,Fort Pierce,West Palm Beach,63.7,Customer Visit
1/6/2016 17:15,1/6/2016 17:19,Business,West Palm Beach,West Palm Beach,4.3,Meal/Entertain
1/6/2016 17:30,1/6/2016 17:35,Business,West Palm Beach,Palm Beach,7.1,Meeting
1/7/2016 13:27,1/7/2016 13:33,Business,Cary,Cary,0.8,Meeting
1/10/2016 8:05,1/10/2016 8:25,Business,Cary,Morrisville,8.3,Meeting
1/10/2016 12:17,1/10/2016 12:44,Business,Jamaica,New York,16.5,Customer Visit
1/10/2016 15:08,1/10/2016 15:51,Business,New York,Queens,10.8,Meeting
1/10/2016 18:18,1/10/2016 18:53,Business,Elmhurst,New York,7.5,Meeting
1/10/2016 19:12,1/10/2016 19:32,Business,Midtown,East Harlem,6.2,Meeting
1/11/2016 8:55,1/11/2016 9:21,Business,East Harlem,NoMad,6.4,Temporary Site
1/11/2016 11:56,1/11/2016 12:03,Business,Flatiron District,Midtown,1.6,Errand/Supplies
1/11/2016 13:32,1/11/2016 13:46,Business,Midtown,Midtown East,1.7,Meal/Entertain
1/11/2016 14:30,1/11/2016 14:43,Business,Midtown East,Midtown,1.9,Meal/Entertain
1/12/2016 12:33,1/12/2016 12:49,Business,Midtown,Hudson Square,1.9,Meal/Entertain
1/12/2016 12:53,1/12/2016 13:09,Business,Hudson Square,Lower Manhattan,4,Meal/Entertain
1/12/2016 14:42,1/12/2016 14:56,Business,Lower Manhattan,Hudson Square,1.8,Errand/Supplies
1/12/2016 15:13,1/12/2016 15:28,Business,Hudson Square,Hell's Kitchen,2.4,Customer Visit
1/12/2016 15:42,1/12/2016 15:54,Business,Hell's Kitchen,Midtown,2,Errand/Supplies
1/12/2016 16:02,1/12/2016 17:00,Business,New York,Queens County,15.1,Meeting
1/13/2016 13:54,1/13/2016 14:07,Business,Downtown,Gulfton,11.2,Meeting
1/13/2016 15:00,1/13/2016 15:28,Business,Gulfton,Downtown,11.8,Meeting
1/14/2016 16:29,1/14/2016 17:05,Business,Houston,Houston,21.9,Customer Visit
1/14/2016 21:39,1/14/2016 21:45,Business,Eagan Park,Jamestown Court,3.9,Errand/Supplies
1/15/2016 0:41,1/15/2016 1:01,Business,Morrisville,Cary,8,Errand/Supplies
1/15/2016 11:43,1/15/2016 12:03,Business,Cary,Durham,10.4,Meal/Entertain
1/15/2016 13:26,1/15/2016 13:44,Business,Durham,Cary,10.4,Meal/Entertain
1/18/2016 14:55,1/18/2016 15:06,Business,Cary,Cary,4.8,Meal/Entertain
1/18/2016 16:13,1/18/2016 16:24,Business,Farmington Woods,Whitebridge,4.7,Meal/Entertain
1/19/2016 9:09,1/19/2016 9:23,Business,Whitebridge,Lake Wellingborough,7.2,
1/19/2016 10:55,1/19/2016 11:09,Business,Lake Wellingborough,Whitebridge,7.6,Temporary Site
1/20/2016 10:36,1/20/2016 11:11,Business,Cary,Raleigh,17.1,Meeting
1/20/2016 11:48,1/20/2016 12:19,Business,Fayetteville Street,Umstead,15.1,Meeting
1/20/2016 13:25,1/20/2016 14:19,Business,Raleigh,Cary,40.2,Customer Visit
1/21/2016 14:25,1/21/2016 14:29,Business,Cary,Cary,1.6,Errand/Supplies
1/21/2016 14:43,1/21/2016 14:51,Business,Cary,Cary,2.4,Meal/Entertain
1/21/2016 16:01,1/21/2016 16:06,Business,Cary,Cary,1,Meal/Entertain
1/26/2016 10:41,1/26/2016 10:50,Business,Whitebridge,Hazelwood,2,Meal/Entertain
1/26/2016 12:33,1/26/2016 12:41,Business,Hazelwood,Whitebridge,2.3,Errand/Supplies
1/26/2016 16:24,1/26/2016 16:32,Business,Whitebridge,Westpark Place,1.9,Errand/Supplies
1/26/2016 17:17,1/26/2016 17:22,Business,Cary,Cary,1.4,Errand/Supplies
1/26/2016 17:27,1/26/2016 17:29,Business,Cary,Cary,0.5,Errand/Supplies
1/27/2016 9:24,1/27/2016 9:31,Business,Cary,Cary,1.8,Meeting
1/27/2016 10:19,1/27/2016 10:48,Business,Cary,Raleigh,18.7,Customer Visit
1/27/2016 12:34,1/27/2016 12:44,Business,Fairmont,Meredith Townes,3.4,Customer Visit
1/27/2016 14:05,1/27/2016 14:13,Business,Raleigh,Raleigh,2.7,Customer Visit
1/27/2016 14:46,1/27/2016 15:08,Business,Raleigh,Cary,12.9,Customer Visit
1/28/2016 12:28,1/28/2016 13:00,Business,Cary,Raleigh,19,Temporary Site
1/28/2016 15:11,1/28/2016 15:31,Business,Meredith Townes,Leesville Hollow,14.7,Meeting
1/28/2016 16:21,1/28/2016 16:51,Business,Raleigh,Cary,15.7,Meeting
1/29/2016 9:31,1/29/2016 9:45,Business,Cary,Cary,4.6,Customer Visit
1/29/2016 10:56,1/29/2016 11:07,Business,Cary,Cary,5.2,Meeting
1/29/2016 11:43,1/29/2016 12:03,Business,Cary,Durham,10.4,Meeting
1/29/2016 13:24,1/29/2016 13:47,Business,Durham,Cary,10.1,Meeting
1/29/2016 18:31,1/29/2016 18:52,Business,Cary,Apex,5.8,Errand/Supplies
1/29/2016 21:21,1/29/2016 21:40,Business,Apex,Cary,5.5,Meal/Entertain
1/30/2016 16:21,1/30/2016 16:33,Business,Cary,Apex,5.7,Errand/Supplies
1/30/2016 18:09,1/30/2016 18:24,Business,Apex,Cary,5.7,Customer Visit
2/1/2016 10:35,2/1/2016 11:15,Business,Cary,Chapel Hill,19.4,Customer Visit
2/1/2016 12:10,2/1/2016 12:43,Business,Chapel Hill,Cary,23.3,Customer Visit
2/1/2016 12:56,2/1/2016 13:07,Business,Northwoods,Whitebridge,3.9,Meal/Entertain
2/2/2016 13:04,2/2/2016 13:23,Business,Whitebridge,Williamsburg Manor,8.3,Meeting
2/2/2016 13:51,2/2/2016 14:06,Business,Cary,Cary,6,Errand/Supplies
2/2/2016 14:38,2/2/2016 14:42,Business,Cary,Cary,1.6,Errand/Supplies
2/4/2016 8:40,2/4/2016 9:01,Business,Cary,Morrisville,5.2,Errand/Supplies
2/4/2016 9:37,2/4/2016 10:09,Business,Morrisville,Cary,9.7,Meal/Entertain
2/4/2016 10:26,2/4/2016 10:32,Business,Cary,Cary,1.6,Meal/Entertain
2/4/2016 15:59,2/4/2016 16:03,Business,Cary,Cary,1.1,Meal/Entertain
2/4/2016 16:35,2/4/2016 16:39,Business,Cary,Cary,1.6,Meal/Entertain
2/4/2016 18:04,2/4/2016 18:31,Business,Whitebridge,Macgregor Downs,9,Meeting
2/4/2016 20:36,2/4/2016 20:55,Business,Cary,Cary,7.7,Meeting
2/5/2016 11:47,2/5/2016 12:07,Business,Cary,Durham,10.4,Meeting
2/5/2016 13:22,2/5/2016 13:41,Business,Durham,Cary,10.4,Meeting
2/6/2016 16:20,2/6/2016 16:53,Business,Cary,Raleigh,11.4,Between Offices
2/6/2016 18:57,2/6/2016 19:21,Business,Raleigh,Cary,9,Errand/Supplies
2/6/2016 19:28,2/6/2016 19:37,Business,Edgehill Farms,Whitebridge,3.2,Meal/Entertain
2/7/2016 16:49,2/7/2016 17:01,Business,Cary,Apex,5.6,Errand/Supplies
2/7/2016 18:03,2/7/2016 18:17,Business,Apex,Cary,5.7,Customer Visit
2/7/2016 18:39,2/7/2016 18:53,Business,Cary,Morrisville,6.1,Temporary Site
2/7/2016 20:22,2/7/2016 20:40,Business,Morrisville,Cary,6.1,Meeting
2/8/2016 12:57,2/8/2016 13:08,Business,Whitebridge,Edgehill Farms,4.3,Meal/Entertain
2/8/2016 14:00,2/8/2016 14:10,Business,Edgehill Farms,Whitebridge,2.7,Meal/Entertain
2/9/2016 10:54,2/9/2016 11:07,Personal,Whitebridge,Northwoods,5.3,
2/9/2016 11:43,2/9/2016 11:50,Personal,Northwoods,Tanglewood,3,
2/9/2016 13:36,2/9/2016 13:52,Personal,Tanglewood,Preston,5.1,
2/9/2016 13:58,2/9/2016 14:02,Personal,Preston,Whitebridge,1.5,
2/9/2016 18:55,2/9/2016 19:11,Business,Cary,Morrisville,6.1,
2/9/2016 20:24,2/9/2016 20:40,Business,Morrisville,Cary,6.1,Meal/Entertain
2/11/2016 16:28,2/11/2016 17:10,Business,Cary,Raleigh,17.3,Meal/Entertain
2/11/2016 17:49,2/11/2016 18:10,Business,Eastgate,Walnut Terrace,5.7,Meal/Entertain
2/11/2016 18:24,2/11/2016 18:46,Business,Raleigh,Morrisville,13.5,Temporary Site
2/11/2016 20:36,2/11/2016 20:51,Business,Morrisville,Cary,6.1,Temporary Site
2/12/2016 8:21,2/12/2016 8:42,Business,Cary,Durham,8.5,Temporary Site
2/12/2016 10:45,2/12/2016 10:52,Business,Durham,Morrisville,2.6,Temporary Site
2/12/2016 11:14,2/12/2016 11:35,Business,Morrisville,Raleigh,17,Customer Visit
2/12/2016 13:02,2/12/2016 13:36,Business,Raleigh,Cary,18,Meeting
2/12/2016 14:49,2/12/2016 15:06,Business,Cary,Morrisville,8.4,Meeting
2/12/2016 15:33,2/12/2016 16:06,Business,Morrisville,Cary,11.5,Customer Visit
2/13/2016 14:21,2/13/2016 14:41,Business,Cary,Morrisville,8.9,Meeting
2/13/2016 23:45,2/14/2016 0:01,Personal,East Elmhurst,Jackson Heights,2.7,
2/14/2016 0:50,2/14/2016 1:00,Personal,Jackson Heights,East Elmhurst,1.8,
2/14/2016 14:07,2/14/2016 14:40,Business,East Elmhurst,New York,8.1,Meeting
2/14/2016 14:46,2/14/2016 15:03,Business,Midtown,Midtown West,2,Meeting
2/14/2016 16:35,2/14/2016 17:02,Business,New York,Long Island City,13,Meeting
2/14/2016 17:06,2/14/2016 17:29,Business,Long Island City,Jamaica,13.9,Meeting
2/16/2016 3:21,2/16/2016 4:13,Business,Katunayaka,Unknown Location,43.7,Customer Visit
2/16/2016 8:29,2/16/2016 9:34,Business,Unknown Location,Colombo,14.1,
2/16/2016 10:31,2/16/2016 10:41,Business,Colombo,Colombo,2.6,
2/16/2016 11:32,2/16/2016 12:02,Business,Colombo,Colombo,4.5,
2/16/2016 12:39,2/16/2016 12:42,Business,Colombo,Colombo,1.7,
2/16/2016 13:43,2/16/2016 13:55,Business,Colombo,Colombo,1.8,Temporary Site
2/16/2016 16:34,2/16/2016 17:10,Business,Colombo,Colombo,6,
2/16/2016 17:17,2/16/2016 17:26,Business,Colombo,Nugegoda,1.1,Meal/Entertain
2/16/2016 17:40,2/16/2016 17:44,Business,Nugegoda,Unknown Location,3.6,Errand/Supplies
2/17/2016 13:18,2/17/2016 14:04,Business,Unknown Location,Colombo,14.7,Temporary Site
2/17/2016 15:17,2/17/2016 15:22,Business,Colombo,Colombo,1.7,Meal/Entertain
2/17/2016 15:33,2/17/2016 16:17,Business,Colombo,Katunayaka,21.4,Temporary Site
2/17/2016 16:38,2/17/2016 16:43,Business,Katunayaka,Katunayaka,0.5,Errand/Supplies
2/18/2016 8:19,2/18/2016 8:27,Business,Unknown Location,Unknown Location,23.5,Temporary Site
2/18/2016 14:03,2/18/2016 14:45,Business,Unknown Location,Islamabad,12.7,Temporary Site
2/18/2016 15:16,2/18/2016 15:31,Business,Islamabad,Unknown Location,6,Temporary Site
2/18/2016 18:44,2/18/2016 18:58,Business,Unknown Location,Islamabad,5.2,Customer Visit
2/18/2016 19:27,2/18/2016 20:08,Business,Islamabad,Unknown Location,10,Meeting
2/19/2016 9:02,2/19/2016 9:14,Business,Unknown Location,Unknown Location,18.3,Meeting
2/19/2016 9:21,2/19/2016 9:51,Business,Unknown Location,Unknown Location,11.2,Meeting
2/19/2016 10:21,2/19/2016 10:48,Business,Unknown Location,Islamabad,7.6,Meeting
2/19/2016 11:20,2/19/2016 11:26,Personal,Islamabad,Islamabad,1.5,
2/19/2016 11:45,2/19/2016 11:50,Personal,Islamabad,Islamabad,1,
2/19/2016 12:09,2/19/2016 12:27,Business,Islamabad,Unknown Location,7.3,Temporary Site
2/19/2016 16:26,2/19/2016 16:45,Business,Unknown Location,Islamabad,3.5,
2/19/2016 17:09,2/19/2016 17:20,Business,Islamabad,Islamabad,4.2,
2/19/2016 20:08,2/19/2016 20:30,Personal,Islamabad,Unknown Location,13.6,
2/19/2016 20:34,2/19/2016 20:51,Personal,Unknown Location,Unknown Location,2.5,
2/20/2016 7:59,2/20/2016 8:32,Personal,Unknown Location,Islamabad,14.4,
2/20/2016 10:48,2/20/2016 10:56,Personal,Islamabad,Islamabad,3,
2/20/2016 11:45,2/20/2016 11:53,Personal,Islamabad,Islamabad,1.5,
2/20/2016 12:41,2/20/2016 13:17,Business,Islamabad,R?walpindi,18.4,
2/20/2016 14:50,2/20/2016 15:54,Business,R?walpindi,R?walpindi,23.1,Meeting
2/20/2016 16:59,2/20/2016 17:54,Personal,R?walpindi,Unknown Location,16.5,
2/20/2016 18:00,2/20/2016 18:03,Business,Unknown Location,Unknown Location,3.2,Errand/Supplies
2/20/2016 19:28,2/20/2016 19:49,Business,Unknown Location,Unknown Location,7.7,Errand/Supplies
2/21/2016 9:07,2/21/2016 9:46,Business,Unknown Location,Islamabad,14.5,
2/21/2016 11:39,2/21/2016 11:43,Business,Unknown Location,Islamabad,2.4,Errand/Supplies
2/21/2016 11:47,2/21/2016 12:01,Business,Islamabad,Islamabad,4.6,Errand/Supplies
2/21/2016 12:13,2/21/2016 12:35,Business,Islamabad,Unknown Location,8.8,Meal/Entertain
2/21/2016 12:51,2/21/2016 13:12,Business,Unknown Location,Unknown Location,8.3,Temporary Site
2/21/2016 13:33,2/21/2016 14:30,Business,Unknown Location,Unknown Location,22.7,Temporary Site
2/21/2016 14:36,2/21/2016 15:03,Business,Unknown Location,Islamabad,13,Temporary Site
2/21/2016 15:14,2/21/2016 15:31,Business,Islamabad,Noorpur Shahan,8.1,Temporary Site
2/21/2016 15:36,2/21/2016 15:41,Business,Noorpur Shahan,Unknown Location,2.2,Meal/Entertain
2/21/2016 16:04,2/21/2016 16:32,Business,Unknown Location,Unknown Location,9.7,
2/21/2016 23:15,2/21/2016 23:52,Business,Unknown Location,R?walpindi,20,Meeting
2/22/2016 21:54,2/22/2016 22:09,Business,Morrisville,Cary,8.1,Customer Visit
2/24/2016 14:30,2/24/2016 14:35,Business,Whitebridge,Preston,1.5,
2/24/2016 15:19,2/24/2016 15:25,Business,Preston,Whitebridge,1.7,Errand/Supplies
2/25/2016 16:27,2/25/2016 16:35,Business,Whitebridge,Heritage Pines,3.1,Errand/Supplies
2/25/2016 16:47,2/25/2016 17:02,Business,Heritage Pines,Whitebridge,3.2,Errand/Supplies
2/25/2016 17:16,2/25/2016 17:36,Business,Whitebridge,Tanglewood,6,Meal/Entertain
2/25/2016 18:22,2/25/2016 18:39,Business,Tanglewood,Whitebridge,5.8,Meal/Entertain
2/26/2016 9:06,2/26/2016 9:29,Business,Whitebridge,Westpark Place,6.3,
2/26/2016 11:05,2/26/2016 11:11,Personal,Westpark Place,Whitebridge,1.7,
2/26/2016 11:35,2/26/2016 11:59,Business,Cary,Durham,10.6,Meeting
2/26/2016 13:01,2/26/2016 13:24,Business,Durham,Cary,9.9,Meeting
2/26/2016 14:38,2/26/2016 14:46,Personal,Whitebridge,Westpark Place,1.9,
2/26/2016 15:00,2/26/2016 15:18,Personal,Westpark Place,Hazelwood,4.2,
2/26/2016 17:01,2/26/2016 17:12,Personal,Hazelwood,Whitebridge,2,
2/28/2016 5:22,2/28/2016 5:38,Business,Whitebridge,Waverly Place,7.7,Meeting
2/28/2016 9:26,2/28/2016 9:42,Business,Waverly Place,Whitebridge,6.8,Meeting
2/29/2016 11:07,2/29/2016 11:14,Personal,Whitebridge,Westpark Place,2.1,
2/29/2016 11:30,2/29/2016 11:40,Business,Cary,Apex,3.8,Meeting
2/29/2016 12:36,2/29/2016 12:48,Business,Apex,Cary,5.6,Meeting
2/29/2016 14:55,2/29/2016 15:03,Business,Whitebridge,Hazelwood,2.6,
2/29/2016 16:40,2/29/2016 17:00,Business,Hazelwood,Whitebridge,6.6,Customer Visit
3/1/2016 18:47,3/1/2016 19:10,Business,Whitebridge,Wayne Ridge,8,Meal/Entertain
3/1/2016 21:27,3/1/2016 21:45,Business,Wayne Ridge,Whitebridge,8,Meeting
3/3/2016 9:45,3/3/2016 9:52,Personal,Whitebridge,Westpark Place,2.2,
3/3/2016 11:04,3/3/2016 11:10,Business,Westpark Place,Whitebridge,2.3,Errand/Supplies
3/3/2016 14:44,3/3/2016 14:58,Business,Whitebridge,Northwoods,5.2,Meal/Entertain
3/3/2016 15:27,3/3/2016 15:48,Business,Cary,Raleigh,7.6,Customer Visit
3/3/2016 16:02,3/3/2016 16:42,Business,Raleigh,Cary,17.3,Meeting
3/4/2016 7:47,3/4/2016 8:06,Business,Cary,Durham,9.9,Meeting
3/4/2016 9:46,3/4/2016 10:03,Business,Durham,Cary,9.9,Customer Visit
3/4/2016 11:46,3/4/2016 12:06,Business,Cary,Durham,10.4,Meeting
3/4/2016 13:03,3/4/2016 13:25,Business,Durham,Cary,10.9,Meeting
3/4/2016 13:40,3/4/2016 14:09,Business,Cary,Raleigh,15.7,Customer Visit
3/4/2016 15:56,3/4/2016 16:08,Business,Raleigh,Raleigh,4.9,Meal/Entertain
3/4/2016 16:16,3/4/2016 16:22,Business,Fayetteville Street,Depot Historic District,0.8,Errand/Supplies
3/4/2016 16:43,3/4/2016 17:12,Business,Raleigh,Cary,13.5,Meeting
3/4/2016 19:02,3/4/2016 19:08,Business,Cary,Morrisville,1.9,Temporary Site
3/4/2016 19:16,3/4/2016 19:25,Business,Morrisville,Cary,2,Meal/Entertain
3/5/2016 11:44,3/5/2016 11:59,Business,Cary,Morrisville,6.5,Meal/Entertain
3/5/2016 12:57,3/5/2016 13:12,Personal,Weston,Weston,4.2,
3/5/2016 14:08,3/5/2016 14:18,Personal,Morrisville,Cary,3.5,
3/5/2016 14:39,3/5/2016 15:01,Business,Whitebridge,Wayne Ridge,7.8,Meal/Entertain
3/5/2016 16:52,3/5/2016 17:13,Business,Cary,Morrisville,7.8,Meal/Entertain
3/5/2016 17:23,3/5/2016 17:34,Business,Morrisville,Cary,3.9,Meal/Entertain
3/7/2016 9:10,3/7/2016 9:20,Business,Whitebridge,Edgehill Farms,2.8,Errand/Supplies
3/7/2016 9:23,3/7/2016 9:47,Business,Cary,Raleigh,12.4,Customer Visit
3/7/2016 12:10,3/7/2016 12:26,Business,Fayetteville Street,Meredith Townes,5.9,Customer Visit
3/7/2016 13:57,3/7/2016 14:18,Business,Meredith Townes,Leesville Hollow,9.4,Meeting
3/7/2016 15:19,3/7/2016 15:45,Business,Raleigh,Cary,11.9,Between Offices
3/8/2016 14:38,3/8/2016 14:55,Business,Whitebridge,Waverly Place,7.2,Between Offices
3/8/2016 15:35,3/8/2016 16:00,Business,Waverly Place,Whitebridge,7.6,Meal/Entertain
3/8/2016 16:13,3/8/2016 16:25,Personal,Whitebridge,Whitebridge,1.6,
3/10/2016 3:36,3/10/2016 3:53,Business,Cary,Morrisville,8.4,Meeting
3/10/2016 10:08,3/10/2016 10:37,Business,East Austin,West University,12.8,Meeting
3/10/2016 14:39,3/10/2016 14:55,Business,West University,South Congress,2.3,
3/10/2016 16:18,3/10/2016 16:28,Business,South Congress,Arts District,1.6,
3/11/2016 9:47,3/11/2016 9:59,Business,The Drag,Congress Ave District,2,Meal/Entertain
3/11/2016 10:29,3/11/2016 10:36,Business,Congress Ave District,Downtown,0.8,
3/11/2016 11:57,3/11/2016 12:04,Business,Downtown,Red River District,1.2,
3/11/2016 13:43,3/11/2016 13:51,Business,Red River District,Downtown,1,
3/11/2016 19:21,3/11/2016 19:35,Business,South Congress,The Drag,2.1,
3/12/2016 9:13,3/12/2016 9:22,Business,The Drag,South Congress,2.2,
3/12/2016 18:27,3/12/2016 18:37,Personal,South Congress,The Drag,1.9,
3/13/2016 9:07,3/13/2016 9:37,Business,The Drag,Convention Center District,5.7,Meal/Entertain
3/13/2016 18:23,3/13/2016 18:43,Business,South Congress,North Austin,8.4,Meal/Entertain
3/13/2016 20:07,3/13/2016 20:28,Business,Georgian Acres,The Drag,6.2,Meal/Entertain
3/13/2016 20:39,3/13/2016 20:58,Business,The Drag,North Austin,10.5,Meal/Entertain
3/13/2016 21:11,3/13/2016 21:23,Business,North Austin,Coxville,7.2,Meal/Entertain
3/13/2016 22:19,3/13/2016 22:39,Business,Coxville,The Drag,12.5,
3/14/2016 8:34,3/14/2016 8:49,Business,The Drag,South Congress,2,Errand/Supplies
3/14/2016 18:39,3/14/2016 18:55,Business,South Congress,The Drag,2.7,
3/15/2016 8:45,3/15/2016 8:57,Business,The Drag,Convention Center District,2,Meal/Entertain
3/15/2016 20:48,3/15/2016 21:01,Business,Downtown,The Drag,2.8,Meal/Entertain
3/16/2016 11:34,3/16/2016 11:45,Business,The Drag,Congress Ave District,1.7,Meal/Entertain
3/16/2016 14:44,3/16/2016 14:55,Business,Convention Center District,West University,2,
3/16/2016 18:43,3/16/2016 18:56,Business,West University,Congress Ave District,2.1,Meal/Entertain
3/17/2016 0:33,3/17/2016 0:44,Personal,Downtown,The Drag,1.7,
3/17/2016 12:52,3/17/2016 15:11,Business,Austin,Katy,136,Customer Visit
3/17/2016 15:16,3/17/2016 15:58,Business,Katy,Houston,30.2,Meeting
3/17/2016 17:20,3/17/2016 18:02,Business,Midtown,Alief,15.5,Meal/Entertain
3/17/2016 18:47,3/17/2016 19:09,Personal,Houston,Houston,4.9,
3/17/2016 20:57,3/17/2016 21:28,Personal,Houston,Houston,12.6,
3/17/2016 21:48,3/17/2016 22:04,Personal,Sharpstown,Midtown,10.4,
3/18/2016 7:15,3/18/2016 7:21,Business,Midtown,Midtown,1.1,Meal/Entertain
3/18/2016 8:35,3/18/2016 8:43,Business,Midtown,Midtown,1.1,Meal/Entertain
3/18/2016 18:24,3/18/2016 19:08,Business,Midtown,Sharpstown,13.2,Meeting
3/18/2016 19:23,3/18/2016 19:29,Business,Sharpstown,Sharpstown,1,Errand/Supplies
3/18/2016 21:01,3/18/2016 21:15,Business,Sharpstown,Midtown,9.2,Customer Visit
3/19/2016 9:10,3/19/2016 9:25,Business,Midtown,Sharpstown,9.4,Meal/Entertain
3/19/2016 12:50,3/19/2016 13:13,Business,Houston,Sugar Land,12,Customer Visit
3/19/2016 14:01,3/19/2016 14:57,Business,Sugar Land,Houston,35.1,Customer Visit
3/19/2016 15:34,3/19/2016 16:38,Business,Houston,Galveston,36.5,Meal/Entertain
3/19/2016 17:17,3/19/2016 17:32,Business,Galveston,Port Bolivar,3.1,Meal/Entertain
3/19/2016 17:37,3/19/2016 17:47,Business,Port Bolivar,Port Bolivar,2.1,Errand/Supplies
3/19/2016 17:52,3/19/2016 18:00,Business,Port Bolivar,Port Bolivar,1.2,
3/19/2016 18:53,3/19/2016 19:29,Business,Port Bolivar,Galveston,7.5,Meeting
3/19/2016 19:33,3/19/2016 20:39,Business,Galveston,Houston,57,Customer Visit
3/20/2016 7:37,3/20/2016 7:48,Business,Midtown,Washington Avenue,5.9,Meeting
3/20/2016 11:42,3/20/2016 11:56,Business,Washington Avenue,Midtown,6.2,Meeting
3/20/2016 17:08,3/20/2016 17:34,Business,Midtown,Sharpstown,10.4,
3/20/2016 18:34,3/20/2016 18:40,Personal,Sharpstown,Briar Meadow,1.2,
3/20/2016 18:45,3/20/2016 19:06,Business,Briar Meadow,Midtown,9.6,Customer Visit
3/21/2016 10:21,3/21/2016 10:26,Personal,Midtown,Downtown,1,
3/21/2016 16:05,3/21/2016 16:13,Business,Downtown,Midtown,0.9,Meal/Entertain
3/21/2016 18:59,3/21/2016 19:15,Business,Midtown,Sharpstown,8.8,
3/21/2016 20:18,3/21/2016 20:55,Business,Sharpstown,Midtown,25.6,Meal/Entertain
3/22/2016 6:17,3/22/2016 6:43,Business,Midtown,Greater Greenspoint,23,Meal/Entertain
3/22/2016 12:06,3/22/2016 12:24,Personal,Morrisville,Cary,8.1,
3/22/2016 19:12,3/22/2016 19:25,Personal,Whitebridge,Whitebridge,1.4,
3/23/2016 14:37,3/23/2016 14:42,Personal,Whitebridge,Preston,1.7,
3/23/2016 14:53,3/23/2016 14:59,Personal,Preston,Whitebridge,1.6,
3/24/2016 19:47,3/24/2016 19:54,Personal,Whitebridge,Westpark Place,2,
3/24/2016 20:34,3/24/2016 20:40,Business,Westpark Place,Whitebridge,2.2,
3/25/2016 13:24,3/25/2016 16:22,Business,Cary,Latta,144,Customer Visit
3/25/2016 16:52,3/25/2016 22:22,Business,Latta,Jacksonville,310.3,Customer Visit
3/25/2016 22:54,3/26/2016 1:39,Business,Jacksonville,Kissimmee,201,Meeting
3/26/2016 14:05,3/26/2016 14:29,Personal,Couples Glen,Isles of Buena Vista,6.7,
3/26/2016 15:19,3/26/2016 15:49,Personal,Kissimmee,Orlando,8.8,
3/26/2016 16:26,3/26/2016 16:30,Personal,Lake Reams,Lake Reams,1.2,
3/27/2016 0:31,3/27/2016 0:40,Business,Lake Reams,Lake Reams,2.1,Errand/Supplies
3/27/2016 1:11,3/27/2016 1:23,Business,Orlando,Kissimmee,6.6,Meal/Entertain
3/27/2016 15:31,3/27/2016 15:56,Business,Kissimmee,Orlando,6.1,Customer Visit
3/27/2016 21:26,3/27/2016 21:41,Personal,Orlando,Orlando,6.9,
3/27/2016 23:04,3/27/2016 23:18,Personal,Orlando,Kissimmee,7.3,
3/28/2016 12:29,3/28/2016 12:42,Personal,Kissimmee,Orlando,3.6,
3/28/2016 19:30,3/28/2016 20:23,Personal,Couples Glen,Vista East,27.2,
3/28/2016 22:55,3/28/2016 23:26,Personal,Orlando,Kissimmee,25.7,
3/29/2016 15:27,3/29/2016 16:11,Personal,Kissimmee,Orlando,13.6,
3/29/2016 18:20,3/29/2016 18:39,Personal,Sand Lake Commons,Sky Lake,6.2,
3/29/2016 20:29,3/29/2016 20:44,Personal,Sky Lake,Sand Lake Commons,6,
3/29/2016 23:04,3/29/2016 23:21,Personal,Orlando,Kissimmee,13.8,
3/30/2016 22:05,3/30/2016 22:55,Business,Orlando,Kissimmee,28.8,Meal/Entertain
3/31/2016 12:47,3/31/2016 13:22,Business,Kissimmee,Orlando,16.1,Temporary Site
3/31/2016 14:37,3/31/2016 15:09,Business,Orlando,Kissimmee,16.4,Meal/Entertain
4/1/2016 13:43,4/1/2016 14:01,Business,Kissimmee,Kissimmee,11,Meeting
4/1/2016 14:36,4/1/2016 15:24,Business,Kissimmee,Orlando,15.5,Customer Visit
4/1/2016 16:01,4/1/2016 16:49,Business,Orlando,Kissimmee,20.3,Meeting
4/1/2016 16:52,4/1/2016 16:57,Personal,Kissimmee,Kissimmee,0.7,
4/2/2016 8:48,4/2/2016 9:04,Personal,Kissimmee,Kissimmee,5.5,
4/2/2016 11:01,4/2/2016 11:16,Personal,Kissimmee,Kissimmee,5.1,
4/2/2016 12:21,4/2/2016 14:47,Business,Kissimmee,Daytona Beach,77.3,Customer Visit
4/2/2016 16:57,4/2/2016 18:09,Business,Daytona Beach,Jacksonville,80.5,Customer Visit
4/2/2016 19:38,4/2/2016 22:36,Business,Jacksonville,Ridgeland,174.2,Customer Visit
4/2/2016 23:11,4/3/2016 1:34,Business,Ridgeland,Florence,144,Meeting
4/3/2016 2:00,4/3/2016 4:16,Business,Florence,Cary,159.3,Meeting
4/5/2016 21:39,4/5/2016 21:55,Business,Whitebridge,Wayne Ridge,7.9,Meal/Entertain
4/6/2016 0:19,4/6/2016 0:39,Business,Wayne Ridge,Whitebridge,8,Meal/Entertain
4/7/2016 18:20,4/7/2016 18:39,Business,Cary,Morrisville,6.1,Meal/Entertain
4/7/2016 19:45,4/7/2016 20:00,Business,Morrisville,Cary,6.1,Errand/Supplies
4/8/2016 12:30,4/8/2016 12:48,Business,Cary,Durham,10.5,Meeting
4/8/2016 13:34,4/8/2016 13:51,Business,Durham,Cary,8.7,Meal/Entertain
4/8/2016 13:55,4/8/2016 14:03,Business,Westpark Place,Whitebridge,1.8,Errand/Supplies
4/8/2016 14:43,4/8/2016 15:20,Business,Cary,Raleigh,19.1,Meeting
4/8/2016 16:05,4/8/2016 16:47,Business,Raleigh,Cary,18.6,Meeting
4/12/2016 9:15,4/12/2016 9:26,Business,Whitebridge,Edgehill Farms,2.8,Errand/Supplies
4/12/2016 9:34,4/12/2016 9:53,Business,Cary,Raleigh,8.9,Meeting
4/12/2016 10:58,4/12/2016 11:18,Business,Meredith,Cedar Hill,7.5,Customer Visit
4/12/2016 12:22,4/12/2016 12:44,Business,Raleigh,Morrisville,15.9,Meeting
4/12/2016 13:42,4/12/2016 14:01,Business,Morrisville,Cary,6.5,Meal/Entertain
4/14/2016 7:29,4/14/2016 8:09,Business,Cary,Holly Springs,15.3,Temporary Site
4/14/2016 16:00,4/14/2016 16:43,Business,Holly Springs,Cary,13.7,Temporary Site
4/15/2016 11:36,4/15/2016 12:07,Business,Cary,Raleigh,11.9,Temporary Site
4/15/2016 12:29,4/15/2016 12:32,Business,Meredith Townes,Harden Place,1.4,Errand/Supplies
4/15/2016 14:31,4/15/2016 15:01,Business,Raleigh,Cary,15.2,Meeting
4/16/2016 12:59,4/16/2016 13:17,Business,Cary,Morrisville,6,Errand/Supplies
4/16/2016 15:10,4/16/2016 15:26,Business,Morrisville,Cary,6.1,Meal/Entertain
4/19/2016 17:44,4/19/2016 18:08,Business,Whitebridge,Wayne Ridge,8.2,Meal/Entertain
4/19/2016 19:57,4/19/2016 20:19,Business,Wayne Ridge,Whitebridge,8,Meal/Entertain
4/22/2016 8:25,4/22/2016 9:04,Business,Cary,Raleigh,13.6,Meeting
4/22/2016 10:10,4/22/2016 10:40,Business,Raleigh,Cary,22.5,Meeting
4/22/2016 12:08,4/22/2016 12:28,Business,Cary,Durham,10.4,Meeting
4/22/2016 13:02,4/22/2016 13:26,Business,Durham,Cary,10,Meeting
4/23/2016 17:03,4/23/2016 17:16,Business,Whitebridge,Tanglewood,6,Meal/Entertain
4/23/2016 18:49,4/23/2016 19:05,Business,Tanglewood,Whitebridge,6.5,Meal/Entertain
4/24/2016 19:07,4/24/2016 19:16,Business,Cary,Morrisville,3.1,Errand/Supplies
4/24/2016 19:46,4/24/2016 19:52,Business,Chessington,Chessington,1.9,Errand/Supplies
4/24/2016 21:41,4/24/2016 21:50,Business,Morrisville,Cary,4.2,Between Offices
4/27/2016 13:30,4/27/2016 13:40,Business,Whitebridge,Burtrose,4.9,Between Offices
4/27/2016 14:13,4/27/2016 14:25,Business,Burtrose,Whitebridge,4.8,Between Offices
4/28/2016 12:09,4/28/2016 12:34,Business,Cary,Raleigh,12.4,Customer Visit
4/28/2016 13:30,4/28/2016 13:49,Business,Raleigh,Cary,32.8,Customer Visit
4/28/2016 22:10,4/28/2016 22:28,Business,Morrisville,Cary,5.5,Customer Visit
4/29/2016 11:44,4/29/2016 12:01,Business,Cary,Durham,9.9,Meeting
4/29/2016 13:13,4/29/2016 13:34,Business,Durham,Cary,10,Meeting
4/29/2016 18:46,4/29/2016 19:18,Business,Cary,Durham,14.2,Customer Visit
4/29/2016 22:44,4/29/2016 23:19,Business,Durham,Cary,18.2,Meeting
4/30/2016 18:42,4/30/2016 18:57,Business,Whitebridge,Waverly Place,7.7,Meal/Entertain
4/30/2016 22:16,4/30/2016 22:34,Business,Waverly Place,Whitebridge,6.8,
5/1/2016 13:45,5/1/2016 13:53,Business,Whitebridge,Westpark Place,2.1,Meal/Entertain
5/1/2016 14:26,5/1/2016 14:31,Business,Westpark Place,Whitebridge,2.3,
5/1/2016 17:33,5/1/2016 17:45,Business,Whitebridge,Tanglewood,6.2,Between Offices
5/1/2016 17:54,5/1/2016 18:10,Business,Tanglewood,Parkway,7.5,Meeting
5/1/2016 22:38,5/1/2016 22:49,Business,Parkway,Whitebridge,3.1,Errand/Supplies
5/2/2016 14:14,5/2/2016 14:21,Business,Whitebridge,Westpark Place,2.2,Errand/Supplies
5/2/2016 15:37,5/2/2016 15:48,Business,Westpark Place,Whitebridge,3.9,Meal/Entertain
5/3/2016 22:20,5/3/2016 22:28,Business,Morrisville,Cary,2.5,Meal/Entertain
5/4/2016 15:16,5/4/2016 15:37,Business,Cary,Morrisville,8.7,Meal/Entertain
5/4/2016 20:55,5/4/2016 21:14,Business,Mcvan,Capitol One,14.5,Errand/Supplies
5/4/2016 21:30,5/4/2016 21:36,Business,Capitol One,University District,4.5,Meal/Entertain
5/4/2016 22:19,5/4/2016 22:27,Business,University District,Capitol One,5,Meal/Entertain
5/5/2016 21:24,5/5/2016 21:36,Business,Seattle,Redmond,14.2,Meal/Entertain
5/5/2016 22:34,5/5/2016 22:40,Business,Redmond,Bellevue,2.9,Errand/Supplies
5/5/2016 23:55,5/6/2016 0:08,Business,Bellevue,Seattle,12.9,Meeting
5/6/2016 5:47,5/6/2016 6:02,Business,Capitol One,Mcvan,14.4,Meeting
5/6/2016 16:45,5/6/2016 16:59,Business,Chapel Hill,Morrisville,17,Meeting
5/6/2016 17:18,5/6/2016 17:44,Business,Morrisville,Cary,7.9,Customer Visit
5/9/2016 6:08,5/9/2016 6:25,Business,Cary,Morrisville,8.4,Customer Visit
5/9/2016 14:39,5/9/2016 15:06,Business,San Francisco,Palo Alto,20.5,Between Offices
5/9/2016 17:58,5/9/2016 18:26,Business,Palo Alto,Sunnyvale,9.8,Customer Visit
5/9/2016 19:35,5/9/2016 19:59,Business,Sunnyvale,Newark,17.6,Customer Visit
5/10/2016 9:03,5/10/2016 9:20,Business,Newark,Menlo Park,9.3,Customer Visit
5/10/2016 17:19,5/10/2016 17:31,Business,Menlo Park,Newark,7.9,Customer Visit
5/11/2016 8:35,5/11/2016 9:12,Business,Newark,San Francisco,25.6,Meeting
5/11/2016 21:47,5/11/2016 22:04,Business,Morrisville,Cary,8.1,Meeting
5/14/2016 18:35,5/14/2016 18:39,Business,Cary,Morrisville,3.1,Meal/Entertain
5/14/2016 23:01,5/14/2016 23:05,Business,Morrisville,Cary,3.1,Meal/Entertain
5/17/2016 13:15,5/17/2016 13:23,Business,Whitebridge,Preston,2.8,Errand/Supplies
5/17/2016 13:56,5/17/2016 14:08,Business,Preston,Westpark Place,2.7,Errand/Supplies
5/17/2016 14:34,5/17/2016 14:40,Business,Westpark Place,Whitebridge,1.9,Errand/Supplies
5/18/2016 9:11,5/18/2016 9:41,Business,Cary,Morrisville,8.4,Customer Visit
5/18/2016 13:00,5/18/2016 13:02,Business,Morrisville,Raleigh,7.6,Customer Visit
5/19/2016 14:37,5/19/2016 15:01,Business,Old City,Parkway Museums,2.9,Meal/Entertain
5/20/2016 10:56,5/20/2016 11:07,Business,Old City,Hog Island,11.2,Meeting
5/20/2016 15:43,5/20/2016 16:12,Business,Morrisville,Cary,8.2,Meal/Entertain
5/22/2016 15:39,5/22/2016 15:46,Business,Cary,Morrisville,3,Meal/Entertain
5/22/2016 18:46,5/22/2016 18:53,Business,Morrisville,Cary,2.5,Meal/Entertain
5/23/2016 20:19,5/23/2016 20:27,Business,Whitebridge,Savon Height,3.6,Meal/Entertain
5/23/2016 21:09,5/23/2016 21:21,Business,Savon Height,Whitebridge,3.6,Errand/Supplies
5/27/2016 20:26,5/27/2016 20:30,Business,Whitebridge,Kildaire Farms,4.5,Errand/Supplies
5/27/2016 20:47,5/27/2016 20:53,Business,Savon Height,Kilarney Woods,1.2,
5/27/2016 22:11,5/27/2016 22:14,Business,Kilarney Woods,Kildaire Farms,1.7,Errand/Supplies
5/28/2016 0:15,5/28/2016 0:21,Business,Kilarney Woods,Whitebridge,4.7,Errand/Supplies
5/28/2016 12:52,5/28/2016 13:06,Business,Cary,Morrisville,6.1,Meal/Entertain
5/28/2016 14:35,5/28/2016 15:04,Business,Morrisville,Cary,11.3,Customer Visit
5/31/2016 13:54,5/31/2016 14:41,Business,Cary,Raleigh,14.9,Meeting
5/31/2016 16:02,5/31/2016 16:39,Business,Raleigh,Cary,14,Meeting
5/31/2016 17:50,5/31/2016 17:59,Business,Westpark Place,Whitebridge,1.8,
6/1/2016 10:19,6/1/2016 10:47,Business,Cary,Morrisville,6.7,Customer Visit
6/1/2016 13:10,6/1/2016 13:39,Business,Morrisville,Cary,9.6,Meeting
6/3/2016 11:29,6/3/2016 11:49,Business,Cary,Durham,10.4,Meeting
6/3/2016 13:08,6/3/2016 13:38,Business,Durham,Cary,9.9,Meeting
6/3/2016 15:31,6/3/2016 15:54,Business,Cary,Morrisville,6,Meal/Entertain
6/3/2016 18:14,6/3/2016 18:29,Business,Townes at Everett Crossing,Chessington,3.3,Errand/Supplies
6/3/2016 18:41,6/3/2016 18:53,Business,Morrisville,Cary,3.1,Errand/Supplies
6/3/2016 19:36,6/3/2016 19:42,Business,Huntington Woods,Weston,1.7,Errand/Supplies
6/3/2016 22:47,6/3/2016 23:06,Business,Morrisville,Cary,4,Between Offices
6/5/2016 14:03,6/5/2016 14:33,Business,Whitebridge,Savon Height,7.8,Customer Visit
6/5/2016 15:06,6/5/2016 15:22,Business,Cary,Morrisville,7.8,Customer Visit
6/5/2016 15:57,6/5/2016 16:08,Business,Weston,Weston,3.8,Meal/Entertain
6/5/2016 18:05,6/5/2016 18:14,Business,Morrisville,Cary,2.5,Meal/Entertain
6/5/2016 21:53,6/5/2016 22:05,Business,Cary,Durham,9.9,Meeting
6/5/2016 23:52,6/6/2016 0:08,Business,Durham,Cary,9.9,Meeting
6/6/2016 15:36,6/6/2016 15:45,Business,Whitebridge,Hazelwood,3,Errand/Supplies
6/6/2016 16:16,6/6/2016 16:24,Business,Hazelwood,Whitebridge,2.4,Errand/Supplies
6/6/2016 20:06,6/6/2016 20:20,Business,Cary,Apex,5.7,Meal/Entertain
6/6/2016 21:08,6/6/2016 21:37,Business,Apex,Cary,7.2,Meal/Entertain
6/6/2016 21:41,6/6/2016 22:00,Business,Cary,Durham,10.4,Meeting
6/6/2016 23:34,6/6/2016 23:48,Business,Durham,Cary,9.9,Meeting
6/7/2016 21:42,6/7/2016 22:00,Business,Cary,Durham,10.4,Meeting
6/7/2016 23:41,6/8/2016 0:04,Business,Durham,Cary,9.9,Meeting
6/8/2016 8:23,6/8/2016 8:53,Business,Cary,Morrisville,8.7,Meal/Entertain
6/8/2016 12:04,6/8/2016 13:01,Business,Jamaica,New York,22.3,Errand/Supplies
6/8/2016 13:12,6/8/2016 13:29,Business,Seaport,Gramercy-Flatiron,3.3,Meal/Entertain
6/8/2016 14:31,6/8/2016 14:37,Business,Medical Centre,Tudor City,0.7,Errand/Supplies
6/8/2016 16:55,6/8/2016 17:11,Business,Rose Hill,Soho,2.5,Meal/Entertain
6/8/2016 17:16,6/8/2016 17:18,Business,Soho,Tribeca,0.5,Errand/Supplies
6/8/2016 17:59,6/8/2016 18:05,Business,Tribeca,Financial District,0.9,Errand/Supplies
6/8/2016 20:11,6/8/2016 20:25,Business,Financial District,Kips Bay,4.8,Errand/Supplies
6/10/2016 15:19,6/10/2016 16:28,Business,New York,Jamaica,16.3,Meeting
6/10/2016 21:47,6/10/2016 22:04,Business,Cary,Durham,10.4,Meeting
6/10/2016 23:53,6/11/2016 0:01,Business,Durham,Cary,9.9,Meeting
6/11/2016 17:08,6/11/2016 17:16,Business,Cary,Morrisville,3.7,Errand/Supplies
6/11/2016 17:34,6/11/2016 17:39,Business,Morrisville,Cary,4.6,Meal/Entertain
6/11/2016 17:50,6/11/2016 17:56,Business,Westpark Place,Whitebridge,1.7,
6/11/2016 21:45,6/11/2016 22:04,Business,Cary,Durham,10.4,Meeting
6/11/2016 23:39,6/12/2016 0:05,Business,Durham,Cary,9.9,Meeting
6/12/2016 19:53,6/12/2016 19:56,Business,Cary,Morrisville,2.5,Meal/Entertain
6/12/2016 20:05,6/12/2016 20:16,Business,Morrisville,Cary,4.3,Errand/Supplies
6/12/2016 21:58,6/12/2016 22:19,Business,Parkway,Whitebridge,2.8,Errand/Supplies
6/13/2016 5:23,6/13/2016 5:42,Business,Cary,Morrisville,8.4,Meal/Entertain
6/13/2016 14:17,6/13/2016 14:46,Business,Oakland,Emeryville,13.2,Meeting
6/13/2016 18:08,6/13/2016 18:47,Business,Emeryville,Berkeley,3.9,Meal/Entertain
6/13/2016 18:54,6/13/2016 19:23,Business,Berkeley,Oakland,5.1,Meal/Entertain
6/13/2016 20:00,6/13/2016 20:05,Business,Oakland,Unknown Location,5.2,Customer Visit
6/14/2016 12:03,6/14/2016 12:21,Business,Emeryville,San Francisco,9.8,
6/14/2016 16:09,6/14/2016 16:39,Business,San Francisco,Emeryville,11.6,Meeting
6/14/2016 17:15,6/14/2016 17:24,Business,Emeryville,Oakland,5.1,Meeting
6/14/2016 17:27,6/14/2016 17:57,Business,Downtown,Bay Farm Island,9.3,Errand/Supplies
6/15/2016 1:46,6/15/2016 2:06,Business,Kenner,New Orleans,12.4,Between Offices
6/15/2016 15:26,6/15/2016 15:34,Business,CBD,Lower Garden District,1.9,Between Offices
6/15/2016 16:37,6/15/2016 17:02,Business,Lower Garden District,Lakeview,6.4,Customer Visit
6/15/2016 17:29,6/15/2016 17:49,Personal,Lakeview,Storyville,5.5,
6/15/2016 19:52,6/15/2016 19:58,Business,Storyville,Faubourg Marigny,1.5,Meal/Entertain
6/16/2016 13:36,6/16/2016 14:30,Business,New Orleans,Metairie,14.5,
6/16/2016 14:42,6/16/2016 14:46,Business,Metairie,Kenner,2.7,
6/16/2016 15:17,6/16/2016 15:41,Business,Kenner,New Orleans,15,
6/16/2016 19:39,6/16/2016 19:56,Business,New Orleans,Kenner,12.9,
6/16/2016 21:43,6/16/2016 21:56,Business,Kenner,New Orleans,13.6,
6/17/2016 16:11,6/17/2016 16:44,Business,New Orleans,Kenner,12.2,
6/18/2016 0:29,6/18/2016 0:51,Business,Morrisville,Cary,8.7,
6/19/2016 2:39,6/19/2016 2:50,Business,Cary,Raleigh,6,
6/19/2016 5:51,6/19/2016 6:00,Business,Raleigh,Cary,5.9,
6/21/2016 15:39,6/21/2016 16:08,Business,Cary,Raleigh,19.3,
6/21/2016 17:11,6/21/2016 18:02,Business,Raleigh,Cary,16.6,Meal/Entertain
6/24/2016 10:41,6/24/2016 10:57,Business,Whitebridge,Waverly Place,7.1,Meal/Entertain
6/24/2016 11:54,6/24/2016 12:01,Business,Waverly Place,Macgregor Downs,2.1,Meal/Entertain
6/24/2016 12:19,6/24/2016 12:37,Business,Cary,Raleigh,8.6,Errand/Supplies
6/24/2016 12:50,6/24/2016 13:12,Business,Raleigh,Morrisville,9,Errand/Supplies
6/24/2016 13:18,6/24/2016 13:27,Business,Morrisville,Cary,3.1,Errand/Supplies
6/24/2016 14:01,6/24/2016 14:20,Business,Cary,Morrisville,8.4,Temporary Site
6/24/2016 20:44,6/24/2016 21:02,Business,Kenner,New Orleans,12.8,
6/25/2016 9:03,6/25/2016 9:12,Business,CBD,Bywater,4.5,
6/25/2016 9:15,6/25/2016 10:08,Business,New Orleans,Chalmette,11.8,Between Offices
6/25/2016 10:18,6/25/2016 10:25,Business,Chalmette,Arabi,1.1,Errand/Supplies
6/25/2016 10:50,6/25/2016 11:18,Business,Arabi,Metairie,17,Meal/Entertain
6/25/2016 11:25,6/25/2016 11:34,Business,Pontchartrain Shores,Pontchartrain Shores,1.7,Meeting
6/25/2016 11:53,6/25/2016 13:21,Business,Metairie,New Orleans,15.5,Meeting
6/25/2016 19:47,6/25/2016 19:58,Business,Storyville,Marigny,1.6,
6/25/2016 23:19,6/25/2016 23:26,Business,Marigny,Storyville,1.5,
6/26/2016 17:43,6/26/2016 18:18,Business,New Orleans,Kenner,12.6,Meeting
6/26/2016 18:45,6/26/2016 19:12,Business,Pontchartrain Shores,Pontchartrain Shores,4.8,
6/26/2016 19:41,6/26/2016 19:50,Business,Kenner,Kenner,2.2,
6/26/2016 21:14,6/26/2016 21:42,Business,Kenner,New Orleans,13,
6/27/2016 7:37,6/27/2016 8:48,Business,New Orleans,Covington,46.9,
6/27/2016 8:51,6/27/2016 9:00,Business,Covington,Covington,2.5,
6/27/2016 9:05,6/27/2016 9:33,Business,Covington,Covington,8.6,
6/27/2016 9:43,6/27/2016 10:08,Business,Covington,Covington,5.2,
6/27/2016 10:22,6/27/2016 10:39,Business,Covington,Covington,7.6,
6/27/2016 10:51,6/27/2016 10:58,Business,Covington,Covington,1.8,
6/27/2016 11:06,6/27/2016 11:24,Business,Covington,Mandeville,4.7,
6/27/2016 11:30,6/27/2016 11:42,Business,Mandeville,Mandeville,2.8,
6/27/2016 12:22,6/27/2016 13:02,Business,Mandeville,Metairie,30,
6/27/2016 13:56,6/27/2016 14:05,Business,Metairie,Kenner,4.4,
6/27/2016 21:09,6/27/2016 21:19,Business,Jamestown Court,Jamestown Court,1,
6/28/2016 0:48,6/28/2016 1:05,Business,Morrisville,Cary,8.2,Customer Visit
6/28/2016 20:13,6/28/2016 20:33,Business,Cary,Durham,10.4,Meeting
6/28/2016 23:34,6/28/2016 23:59,Business,Durham,Cary,9.9,Meeting
6/28/2016 23:34,6/28/2016 23:59,Business,Durham,Cary,9.9,Meeting
6/29/2016 8:56,6/29/2016 9:24,Business,Cary,Morrisville,7.3,
6/29/2016 10:22,6/29/2016 10:38,Business,Morrisville,Cary,7.4,
6/29/2016 11:49,6/29/2016 11:51,Business,Whitebridge,Westpark Place,1.6,
6/29/2016 12:11,6/29/2016 12:16,Business,Westpark Place,Whitebridge,1.8,
6/29/2016 20:11,6/29/2016 20:29,Business,Cary,Durham,10.4,Meeting
6/29/2016 23:38,6/30/2016 0:00,Business,Durham,Cary,9.9,Meeting
6/30/2016 20:09,6/30/2016 20:26,Business,Cary,Durham,9.9,Meeting
7/1/2016 0:00,7/1/2016 0:25,Business,Durham,Cary,9.9,Meeting
7/1/2016 9:34,7/1/2016 9:57,Business,Cary,Raleigh,13.3,Meeting
7/1/2016 12:36,7/1/2016 13:00,Business,Raleigh,Cary,11.3,Meeting
7/1/2016 20:06,7/1/2016 20:24,Business,Cary,Durham,10.5,Meeting
7/1/2016 23:48,7/2/2016 0:09,Business,Durham,Cary,9.9,Meeting
7/2/2016 20:18,7/2/2016 20:36,Business,Cary,Durham,10.1,Meeting
7/2/2016 23:48,7/3/2016 0:12,Business,Durham,Cary,9.9,Meeting
7/3/2016 0:28,7/3/2016 0:38,Business,Cary,Morrisville,3.1,Errand/Supplies
7/3/2016 3:02,7/3/2016 3:08,Business,Morrisville,Cary,3.1,Errand/Supplies
7/3/2016 20:00,7/3/2016 20:18,Business,Cary,Durham,9.9,Meeting
7/4/2016 0:32,7/4/2016 0:47,Business,Durham,Cary,9.9,Meeting
7/4/2016 17:31,7/4/2016 17:49,Business,Whitebridge,Summerwinds,8.8,Meeting
7/4/2016 18:23,7/4/2016 18:49,Business,Summerwinds,Whitebridge,8.7,Temporary Site
7/4/2016 20:00,7/4/2016 20:17,Business,Cary,Durham,11.8,Meeting
7/5/2016 0:00,7/5/2016 0:05,Business,Parkwood,Parkwood,1.2,Errand/Supplies
7/5/2016 0:08,7/5/2016 0:28,Business,Durham,Cary,9.9,Meeting
7/5/2016 16:48,7/5/2016 16:52,Business,Whitebridge,Whitebridge,0.6,Errand/Supplies
7/5/2016 20:06,7/5/2016 20:26,Business,Cary,Durham,9.9,
7/5/2016 22:41,7/5/2016 23:02,Business,Durham,Morrisville,8.6,
7/6/2016 0:33,7/6/2016 0:53,Business,Morrisville,Cary,6.3,Meal/Entertain
7/6/2016 9:06,7/6/2016 9:25,Business,Cary,Durham,9.9,Meeting
7/6/2016 12:48,7/6/2016 13:08,Business,Durham,Cary,9.9,
7/6/2016 20:04,7/6/2016 20:14,Business,Cary,Morrisville,3.3,Meal/Entertain
7/6/2016 23:46,7/6/2016 23:59,Business,Morrisville,Cary,3.1,Customer Visit
7/7/2016 8:22,7/7/2016 8:50,Business,Cary,Morrisville,7.9,Temporary Site
7/7/2016 10:27,7/7/2016 10:33,Business,Morrisville,Cary,8.9,
7/7/2016 12:59,7/7/2016 13:35,Business,Kenner,New Orleans,12.8,
7/8/2016 9:50,7/8/2016 10:13,Business,CBD,Pontchartrain Beach,7.7,
7/8/2016 10:51,7/8/2016 11:12,Business,Pontchartrain Beach,CBD,7,
7/8/2016 13:48,7/8/2016 14:11,Business,New Orleans,Metairie,12.5,
7/8/2016 17:11,7/8/2016 17:30,Business,Kenner,New Orleans,13.2,
7/9/2016 9:03,7/9/2016 9:46,Business,New Orleans,Kenner,13,
7/9/2016 9:52,7/9/2016 10:06,Business,Kenner,Metairie,4.9,
7/9/2016 10:15,7/9/2016 10:33,Business,Metairie,New Orleans,8.5,
7/10/2016 14:10,7/10/2016 14:17,Business,CBD,St Thomas,1.3,
7/10/2016 16:04,7/10/2016 16:15,Business,St Thomas,CBD,1.8,
7/10/2016 18:05,7/10/2016 18:21,Business,New Orleans,Kenner,13.6,
7/10/2016 19:51,7/10/2016 20:08,Business,Kenner,New Orleans,13.4,
7/12/2016 16:10,7/12/2016 16:45,Business,New Orleans,Kenner,12.3,
7/12/2016 19:21,7/12/2016 19:26,Personal,Kenner,Kenner,1.4,
7/12/2016 23:47,7/13/2016 0:11,Personal,Morrisville,Cary,8.7,
7/13/2016 12:39,7/13/2016 13:20,Personal,Cary,Morrisville,23.5,
7/13/2016 13:25,7/13/2016 13:39,Personal,Morrisville,Morrisville,2.2,
7/13/2016 13:42,7/13/2016 13:54,Personal,Morrisville,Cary,4.4,
7/14/2016 15:51,7/14/2016 15:59,Personal,Cary,Morrisville,3.3,
7/14/2016 16:03,7/14/2016 16:34,Business,Morrisville,Morrisville,11.8,Errand/Supplies
7/14/2016 16:39,7/14/2016 20:05,Business,Morrisville,Banner Elk,195.3,
7/15/2016 11:32,7/15/2016 11:53,Personal,Banner Elk,Banner Elk,8.3,
7/15/2016 12:09,7/15/2016 12:19,Personal,Banner Elk,Banner Elk,3.2,
7/15/2016 12:35,7/15/2016 13:15,Personal,Banner Elk,Elk Park,22.4,
7/15/2016 15:03,7/15/2016 15:33,Personal,Elk Park,Banner Elk,12.2,
7/15/2016 15:40,7/15/2016 15:52,Personal,Banner Elk,Banner Elk,4.5,
7/16/2016 13:14,7/16/2016 14:10,Personal,Banner Elk,Newland,28.1,
7/16/2016 14:14,7/16/2016 14:30,Personal,Newland,Newland,3.8,
7/16/2016 15:29,7/16/2016 16:57,Personal,Newland,Boone,41.9,
7/16/2016 19:42,7/16/2016 20:35,Personal,Boone,Banner Elk,23.8,
7/16/2016 21:45,7/16/2016 22:18,Personal,Banner Elk,Banner Elk,13,
7/16/2016 22:50,7/16/2016 23:03,Business,Banner Elk,Banner Elk,4.4,Errand/Supplies
7/17/2016 11:23,7/17/2016 11:50,Personal,Banner Elk,Boone,15.1,Charity ($)
7/17/2016 12:20,7/17/2016 15:25,Personal,Boone,Cary,180.2,Commute
7/18/2016 10:37,7/18/2016 10:49,Personal,Cary,Morrisville,4.1,Moving
7/18/2016 10:54,7/18/2016 11:15,Personal,Morrisville,Cary,6.1,Moving
7/18/2016 11:25,7/18/2016 11:36,Personal,Northwoods,Preston,3.3,Moving
7/18/2016 11:40,7/18/2016 11:56,Personal,Preston,Whitebridge,4.7,Moving
7/18/2016 17:12,7/18/2016 17:33,Business,Cary,Apex,7.2,Meeting
7/18/2016 18:32,7/18/2016 18:47,Business,Apex,Cary,5.5,Meal/Entertain
7/18/2016 19:07,7/18/2016 19:14,Business,Cary,Morrisville,3.3,Meal/Entertain
7/18/2016 20:28,7/18/2016 20:32,Business,Hazelwood,Weston,0.9,Errand/Supplies
7/18/2016 21:11,7/18/2016 21:19,Business,Morrisville,Cary,3.8,Meal/Entertain
7/19/2016 10:35,7/19/2016 10:51,Business,Whitebridge,Stonewater,6.4,Customer Visit
7/19/2016 10:56,7/19/2016 11:11,Business,Stonewater,Lexington Park at Amberly,3,Meeting
7/19/2016 11:30,7/19/2016 12:00,Business,Lexington Park at Amberly,Whitebridge,8.7,Meal/Entertain
7/19/2016 17:14,7/19/2016 17:24,Business,Whitebridge,Chessington,3.9,Errand/Supplies
7/19/2016 17:50,7/19/2016 18:08,Personal,Chessington,Whitebridge,4.8,
7/20/2016 17:12,7/20/2016 17:24,Personal,Whitebridge,Edgehill Farms,2.8,
7/20/2016 17:50,7/20/2016 17:57,Personal,Edgehill Farms,Preston,1.4,
7/20/2016 18:16,7/20/2016 18:20,Personal,Preston,Whitebridge,1.4,
7/21/2016 17:17,7/21/2016 17:23,Business,Whitebridge,Edgehill Farms,2.7,
7/21/2016 17:42,7/21/2016 17:51,Business,Edgehill Farms,Burtrose,2.3,
7/21/2016 18:27,7/21/2016 18:42,Business,Cary,Morrisville,3.7,
7/21/2016 19:30,7/21/2016 19:39,Business,Morrisville,Cary,2.9,
7/22/2016 10:42,7/22/2016 10:53,Business,Cary,Morrisville,3.8,
7/22/2016 11:11,7/22/2016 11:25,Business,Morrisville,Cary,5.1,
7/22/2016 11:37,7/22/2016 12:00,Business,Hazelwood,Lexington Park at Amberly,9.1,
7/22/2016 12:14,7/22/2016 12:31,Business,Cary,Durham,8,
7/22/2016 13:21,7/22/2016 13:42,Business,Durham,Cary,9.9,Meeting
7/22/2016 14:27,7/22/2016 14:43,Business,Cary,Morrisville,6.1,Meal/Entertain
7/22/2016 15:49,7/22/2016 16:22,Business,Morrisville,Cary,12.2,
7/22/2016 18:33,7/22/2016 18:51,Business,Wayne Ridge,Whitebridge,8,
7/23/2016 14:27,7/23/2016 14:44,Business,Cary,Morrisville,4,
7/23/2016 14:48,7/23/2016 15:12,Business,Morrisville,Cary,9.5,
7/23/2016 15:15,7/23/2016 15:27,Business,Cary,Morrisville,3,
7/23/2016 15:50,7/23/2016 16:10,Business,Morrisville,Cary,6.3,
7/23/2016 20:17,7/23/2016 20:33,Business,Cary,Durham,10.4,Meeting
7/23/2016 23:18,7/23/2016 23:43,Business,Durham,Cary,9.9,Meeting
7/25/2016 10:35,7/25/2016 10:41,Business,Whitebridge,Parkway,1.5,
7/25/2016 10:47,7/25/2016 10:58,Business,Cary,Morrisville,4.9,
7/25/2016 11:04,7/25/2016 11:33,Business,Morrisville,Cary,7.9,
7/25/2016 11:37,7/25/2016 11:44,Business,Parkway,Whitebridge,1.7,
7/26/2016 15:43,7/26/2016 15:49,Business,Whitebridge,Westpark Place,2.2,
7/26/2016 17:14,7/26/2016 17:24,Business,Westpark Place,Whitebridge,2.1,
7/26/2016 20:52,7/26/2016 21:00,Business,Cary,Morrisville,2.5,Meal/Entertain
7/26/2016 22:31,7/26/2016 22:39,Business,Morrisville,Cary,2.5,Meal/Entertain
7/27/2016 19:08,7/27/2016 19:20,Business,Cary,Morrisville,2.8,
7/27/2016 21:34,7/27/2016 21:57,Business,Morrisville,Raleigh,14.7,
7/27/2016 22:00,7/27/2016 22:26,Business,Raleigh,Morrisville,14.6,
7/28/2016 0:04,7/28/2016 0:09,Business,Morrisville,Cary,2.3,
7/29/2016 15:45,7/29/2016 15:47,Business,Whitebridge,Westpark Place,2.2,
7/29/2016 17:27,7/29/2016 17:45,Business,Westpark Place,Whitebridge,2.2,Meal/Entertain
7/30/2016 17:02,7/30/2016 17:27,Business,Cary,Durham,14,
7/30/2016 21:16,7/30/2016 21:41,Business,Durham,Cary,13.3,
7/31/2016 17:30,7/31/2016 17:37,Business,Westpark Place,Whitebridge,1.8,
8/1/2016 12:47,8/1/2016 13:04,Business,Whitebridge,Arlington Park at Amberly,6.2,
8/1/2016 13:08,8/1/2016 13:19,Business,Arlington Park at Amberly,Lexington Park at Amberly,1.3,
8/1/2016 13:28,8/1/2016 13:46,Business,Lexington Park at Amberly,Westpark Place,1.9,
8/1/2016 13:52,8/1/2016 14:14,Business,Cary,Apex,6.9,
8/1/2016 15:40,8/1/2016 15:47,Business,Apex,Cary,4.6,
8/1/2016 16:18,8/1/2016 16:25,Business,Whitebridge,Edgehill Farms,2.8,
8/1/2016 16:29,8/1/2016 16:59,Business,Cary,Morrisville,9.1,
8/1/2016 17:23,8/1/2016 17:55,Business,Morrisville,Cary,8.1,
8/2/2016 8:11,8/2/2016 8:32,Business,Cary,Morrisville,8.4,Meeting
8/2/2016 11:51,8/2/2016 12:15,Business,Arlington,Washington,4.9,
8/2/2016 19:15,8/2/2016 19:23,Business,Kalorama Triangle,K Street,1,
8/2/2016 21:23,8/2/2016 21:29,Business,K Street,Kalorama Triangle,1,
8/3/2016 12:46,8/3/2016 13:00,Business,West End,Northwest Rectangle,2,
8/3/2016 14:59,8/3/2016 15:03,Business,K Street,Kalorama Triangle,1.1,
8/3/2016 16:00,8/3/2016 16:04,Business,Kalorama Triangle,Downtown,1.5,
8/5/2016 17:23,8/5/2016 17:30,Business,Connecticut Avenue,Kalorama Triangle,1.3,
8/5/2016 18:17,8/5/2016 18:21,Business,Kalorama Triangle,Columbia Heights,1.8,
8/5/2016 19:17,8/5/2016 19:27,Business,Columbia Heights,Kalorama Triangle,1.5,
8/6/2016 6:40,8/6/2016 6:58,Business,Washington,Arlington,6.6,
8/6/2016 9:31,8/6/2016 9:53,Business,Morrisville,Cary,8,
8/7/2016 17:14,8/7/2016 17:23,Business,Whitebridge,Edgehill Farms,2.7,
8/7/2016 17:28,8/7/2016 17:43,Business,Edgehill Farms,Whitebridge,2.7,Customer Visit
8/7/2016 18:17,8/7/2016 18:23,Business,Cary,Morrisville,2.5,
8/7/2016 20:15,8/7/2016 20:23,Business,Morrisville,Cary,2.5,Meal/Entertain
8/8/2016 16:17,8/8/2016 16:31,Business,Whitebridge,Farmington Woods,5.2,
8/8/2016 16:37,8/8/2016 16:50,Business,Farmington Woods,Edgehill Farms,4,
8/8/2016 17:02,8/8/2016 17:13,Business,Edgehill Farms,Whitebridge,2.7,Customer Visit
8/8/2016 21:50,8/8/2016 22:15,Business,Cary,Morrisville,4.8,
8/8/2016 23:28,8/8/2016 23:37,Business,Morrisville,Cary,3.2,Customer Visit
8/9/2016 14:20,8/9/2016 14:38,Business,Whitebridge,Waverly Place,6.9,
8/9/2016 15:15,8/9/2016 15:36,Business,Cary,Raleigh,14.9,
8/9/2016 16:04,8/9/2016 16:37,Business,Raleigh,Cary,17.4,
8/10/2016 16:56,8/10/2016 17:24,Business,Cary,Durham,12.9,
8/10/2016 17:53,8/10/2016 18:28,Business,Durham,Apex,15.3,
8/10/2016 18:49,8/10/2016 18:50,Business,Apex,Apex,1,
8/10/2016 19:47,8/10/2016 20:02,Business,Apex,Cary,6,
8/11/2016 12:53,8/11/2016 13:00,Business,Whitebridge,Heritage Pines,2.2,
8/11/2016 13:14,8/11/2016 13:28,Business,Heritage Pines,Edgehill Farms,4.4,
8/11/2016 13:32,8/11/2016 13:42,Business,Edgehill Farms,Whitebridge,2.8,
8/11/2016 18:37,8/11/2016 19:29,Business,Cary,Wake Forest,31.7,
8/11/2016 20:59,8/11/2016 21:44,Business,Wake Forest,Cary,31.9,
8/12/2016 18:49,8/12/2016 18:52,Business,Whitebridge,Westpark Place,1.9,
8/12/2016 18:56,8/12/2016 19:05,Business,Westpark Place,Whitebridge,1.8,
8/13/2016 15:35,8/13/2016 15:58,Business,Cary,Morrisville,8.4,Meeting
8/15/2016 9:05,8/15/2016 9:52,Business,R?walpindi,Unknown Location,15.6,
8/15/2016 15:20,8/15/2016 15:47,Business,Unknown Location,Unknown Location,14.1,
8/15/2016 16:52,8/15/2016 17:30,Business,Unknown Location,Unknown Location,15.7,
8/15/2016 19:08,8/15/2016 20:30,Business,Unknown Location,Unknown Location,25.9,Temporary Site
8/16/2016 7:58,8/16/2016 8:11,Business,Unknown Location,Unknown Location,7.9,
8/16/2016 8:16,8/16/2016 8:23,Business,Unknown Location,Unknown Location,2.7,
8/16/2016 8:46,8/16/2016 8:53,Business,Unknown Location,Unknown Location,5.5,
8/16/2016 10:06,8/16/2016 10:27,Business,Unknown Location,Islamabad,5.7,
8/16/2016 10:31,8/16/2016 10:38,Business,Islamabad,Islamabad,1.2,
8/16/2016 11:47,8/16/2016 12:03,Business,Islamabad,Unknown Location,5.7,Temporary Site
8/16/2016 15:13,8/16/2016 15:36,Business,Unknown Location,Unknown Location,16.2,
8/17/2016 10:17,8/17/2016 10:41,Business,Unknown Location,Unknown Location,2.6,
8/17/2016 10:57,8/17/2016 11:20,Business,Unknown Location,Unknown Location,12.1,
8/17/2016 14:45,8/17/2016 14:50,Business,Unknown Location,R?walpindi,1.4,
8/17/2016 15:32,8/17/2016 15:47,Business,R?walpindi,Islamabad,6.4,
8/17/2016 16:29,8/17/2016 16:50,Business,Islamabad,Unknown Location,7.3,
8/17/2016 16:54,8/17/2016 17:00,Business,Unknown Location,Unknown Location,5.3,
8/17/2016 17:05,8/17/2016 17:34,Business,Unknown Location,Unknown Location,5.5,
8/17/2016 18:38,8/17/2016 18:57,Business,Unknown Location,Unknown Location,7.7,Temporary Site
8/18/2016 18:40,8/18/2016 19:07,Business,Unknown Location,Unknown Location,7.6,Temporary Site
8/19/2016 8:24,8/19/2016 8:45,Business,Unknown Location,Noorpur Shahan,7.6,
8/19/2016 8:54,8/19/2016 9:07,Business,Noorpur Shahan,Islamabad,3.3,
8/19/2016 9:27,8/19/2016 9:47,Business,Islamabad,R?walpindi,6.5,
8/19/2016 10:57,8/19/2016 11:06,Business,R?walpindi,Unknown Location,2,
8/19/2016 12:07,8/19/2016 12:24,Business,Unknown Location,Islamabad,5.7,
8/19/2016 15:51,8/19/2016 16:06,Business,Islamabad,Islamabad,3.2,
8/19/2016 17:12,8/19/2016 17:52,Business,Islamabad,Unknown Location,12.5,
8/21/2016 10:00,8/21/2016 10:29,Business,Unknown Location,Unknown Location,7.6,Airport/Travel
8/21/2016 14:05,8/21/2016 14:34,Business,Unknown Location,Unknown Location,7.7,
8/21/2016 16:30,8/21/2016 17:02,Business,Unknown Location,Islamabad,12.2,
8/21/2016 18:10,8/21/2016 18:17,Business,Islamabad,Islamabad,1.4,
8/21/2016 18:48,8/21/2016 19:24,Business,Islamabad,Unknown Location,20.2,
8/22/2016 10:00,8/22/2016 10:44,Business,Unknown Location,Islamabad,9.8,
8/22/2016 11:07,8/22/2016 11:23,Business,Islamabad,Unknown Location,6.3,
8/22/2016 12:36,8/22/2016 12:49,Business,Unknown Location,Islamabad,4.9,
8/22/2016 13:02,8/22/2016 13:11,Business,Islamabad,Islamabad,1.5,
8/22/2016 14:07,8/22/2016 14:31,Business,Islamabad,Unknown Location,10.9,
8/22/2016 15:14,8/22/2016 15:49,Business,Unknown Location,Unknown Location,19,
8/22/2016 15:59,8/22/2016 17:16,Business,Unknown Location,Unknown Location,19,
8/22/2016 19:58,8/22/2016 20:50,Business,Unknown Location,R?walpindi,7.9,
8/22/2016 20:53,8/22/2016 21:31,Business,R?walpindi,R?walpindi,4.1,
8/22/2016 22:31,8/22/2016 23:00,Business,R?walpindi,Unknown Location,18.7,
8/23/2016 8:10,8/23/2016 8:25,Business,Unknown Location,Noorpur Shahan,8.7,
8/23/2016 9:35,8/23/2016 10:09,Business,Noorpur Shahan,Unknown Location,7.5,
8/23/2016 12:59,8/23/2016 13:15,Business,Unknown Location,Noorpur Shahan,7.7,
8/23/2016 13:19,8/23/2016 13:30,Business,Noorpur Shahan,Islamabad,4.4,
8/23/2016 13:49,8/23/2016 14:04,Business,Islamabad,Unknown Location,5,
8/23/2016 15:07,8/23/2016 15:12,Business,Unknown Location,Unknown Location,1.9,
8/23/2016 15:15,8/23/2016 17:16,Business,Unknown Location,Unknown Location,7.9,
8/23/2016 17:42,8/23/2016 18:31,Business,Unknown Location,Unknown Location,17.7,
8/24/2016 12:05,8/24/2016 12:56,Business,Unknown Location,Unknown Location,25.2,
8/24/2016 13:01,8/24/2016 15:25,Business,Unknown Location,Unknown Location,96.2,
8/25/2016 15:17,8/25/2016 16:22,Business,Unknown Location,Unknown Location,35,
8/25/2016 16:36,8/25/2016 16:56,Business,Unknown Location,Unknown Location,5.5,
8/25/2016 17:19,8/25/2016 19:20,Business,Unknown Location,Unknown Location,50.4,
8/25/2016 19:25,8/25/2016 19:57,Business,Unknown Location,Lahore,9.2,
8/25/2016 22:58,8/25/2016 23:16,Business,Lahore,Unknown Location,7.3,
8/26/2016 9:06,8/26/2016 9:20,Business,Unknown Location,Unknown Location,5,
8/26/2016 11:14,8/26/2016 11:26,Business,Unknown Location,Unknown Location,3.8,
8/26/2016 12:10,8/26/2016 12:20,Business,Unknown Location,Lahore,3.9,
8/26/2016 14:10,8/26/2016 14:33,Business,Lahore,Lahore,7.4,
8/26/2016 15:23,8/26/2016 15:35,Business,Lahore,Lahore,1.5,
8/26/2016 15:59,8/26/2016 16:24,Business,Lahore,Unknown Location,7.9,
8/26/2016 16:55,8/26/2016 17:12,Business,Unknown Location,Lahore,2.9,
8/26/2016 18:42,8/26/2016 18:56,Business,Lahore,Lahore,3.4,
8/26/2016 19:31,8/26/2016 19:54,Business,Lahore,Lahore,3.8,
8/26/2016 20:06,8/26/2016 20:16,Business,Lahore,Unknown Location,5.9,
8/27/2016 9:34,8/27/2016 10:11,Business,Unknown Location,Lahore,9.6,
8/27/2016 11:47,8/27/2016 12:06,Business,Lahore,Lahore,7,
8/27/2016 12:12,8/27/2016 12:17,Business,Lahore,Lahore,0.9,
8/27/2016 14:01,8/27/2016 15:44,Business,Lahore,Unknown Location,86.6,
8/27/2016 16:15,8/27/2016 19:13,Business,Unknown Location,Unknown Location,156.9,
8/28/2016 9:57,8/28/2016 10:18,Business,Unknown Location,Noorpur Shahan,10.1,
8/28/2016 16:39,8/28/2016 16:55,Business,Noorpur Shahan,Islamabad,6.2,
8/28/2016 17:37,8/28/2016 17:55,Business,Islamabad,Islamabad,5.3,
8/28/2016 21:15,8/28/2016 21:59,Business,Islamabad,Unknown Location,12.1,
8/29/2016 12:02,8/29/2016 12:31,Business,Unknown Location,Islamabad,10.8,
8/29/2016 13:38,8/29/2016 13:48,Business,Islamabad,Islamabad,4.3,
8/29/2016 14:31,8/29/2016 14:41,Business,Islamabad,Islamabad,2.5,
8/29/2016 14:49,8/29/2016 15:04,Business,Islamabad,Unknown Location,5.7,Temporary Site
8/29/2016 15:49,8/29/2016 15:59,Business,Unknown Location,Islamabad,2.8,
8/29/2016 16:06,8/29/2016 16:21,Business,Islamabad,Unknown Location,4,
8/29/2016 17:24,8/29/2016 17:41,Business,Unknown Location,Islamabad,5.5,
8/29/2016 18:27,8/29/2016 18:36,Business,Islamabad,Islamabad,2.6,
8/30/2016 11:53,8/30/2016 12:05,Business,Unknown Location,Unknown Location,2.1,
8/30/2016 12:46,8/30/2016 13:09,Business,Unknown Location,Islamabad,8.8,
8/30/2016 13:25,8/30/2016 13:46,Business,Islamabad,Islamabad,4.4,
8/30/2016 14:00,8/30/2016 14:20,Business,Islamabad,Unknown Location,5.3,
8/30/2016 17:27,8/30/2016 18:09,Business,Unknown Location,Unknown Location,13,
9/1/2016 11:51,9/1/2016 12:24,Business,Unknown Location,Islamabad,13,
9/1/2016 17:21,9/1/2016 17:36,Business,Islamabad,Unknown Location,10.6,
9/1/2016 18:49,9/1/2016 19:08,Business,Unknown Location,Unknown Location,2.2,
9/2/2016 11:37,9/2/2016 12:24,Business,Unknown Location,Islamabad,9.2,
9/2/2016 18:56,9/2/2016 19:37,Business,Unknown Location,Unknown Location,12.9,
9/5/2016 10:25,9/5/2016 10:44,Business,Unknown Location,R?walpindi,17.2,
9/6/2016 17:49,9/6/2016 17:49,Business,Unknown Location,Unknown Location,69.1,
9/10/2016 10:28,9/10/2016 10:45,Business,Unknown Location,Unknown Location,2.8,
9/11/2016 9:51,9/11/2016 9:55,Business,Unknown Location,Unknown Location,8.6,
9/11/2016 21:40,9/11/2016 21:42,Business,Unknown Location,Unknown Location,9.8,
9/12/2016 8:07,9/12/2016 8:12,Business,Unknown Location,Unknown Location,3.6,
9/12/2016 11:15,9/12/2016 11:24,Business,Unknown Location,Unknown Location,1.7,
9/12/2016 13:04,9/12/2016 13:44,Business,Unknown Location,Unknown Location,11.5,
9/13/2016 16:56,9/13/2016 17:02,Business,Unknown Location,Unknown Location,0.7,
9/14/2016 11:55,9/14/2016 11:59,Business,Unknown Location,Unknown Location,0.7,
9/15/2016 20:33,9/15/2016 20:38,Business,Unknown Location,Unknown Location,0.9,
9/16/2016 7:08,9/16/2016 7:08,Business,Unknown Location,Unknown Location,1.6,
9/18/2016 18:07,9/18/2016 18:11,Business,Unknown Location,Unknown Location,9.4,
9/19/2016 6:18,9/19/2016 6:49,Business,R?walpindi,Unknown Location,18.2,
9/19/2016 14:40,9/19/2016 14:56,Business,Unknown Location,Islamabad,10.5,
9/19/2016 16:23,9/19/2016 16:31,Business,Islamabad,Unknown Location,5.7,
9/19/2016 17:36,9/19/2016 18:20,Business,Unknown Location,Unknown Location,18,
9/19/2016 19:10,9/19/2016 19:49,Business,Unknown Location,Islamabad,18.3,
9/20/2016 11:29,9/20/2016 11:48,Business,Islamabad,Unknown Location,16.5,
9/20/2016 20:47,9/20/2016 22:47,Business,Unknown Location,R?walpindi,9.6,
9/23/2016 13:15,9/23/2016 13:40,Business,Karachi,Karachi,2.9,
9/24/2016 14:34,9/24/2016 15:15,Business,Karachi,Unknown Location,8.2,
9/24/2016 20:29,9/24/2016 20:33,Business,Unknown Location,Unknown Location,2.4,
9/27/2016 8:33,9/27/2016 8:35,Business,Unknown Location,Unknown Location,5.8,
9/27/2016 13:21,9/27/2016 14:43,Business,Lahore,Lahore,9.8,
9/27/2016 19:14,9/27/2016 20:34,Business,Lahore,Unknown Location,7.3,
9/27/2016 21:01,9/28/2016 2:37,Business,Unknown Location,Unknown Location,195.6,
9/28/2016 17:21,9/28/2016 19:36,Business,Islamabad,Unknown Location,20.5,
9/29/2016 16:13,9/29/2016 18:47,Business,Unknown Location,Islamabad,12.6,
9/30/2016 17:39,9/30/2016 20:20,Business,Islamabad,Islamabad,37.7,
9/30/2016 20:59,9/30/2016 22:34,Business,Islamabad,Unknown Location,16.7,
10/3/2016 17:09,10/3/2016 17:12,Business,Unknown Location,Islamabad,10.5,
10/3/2016 18:17,10/3/2016 18:34,Business,Islamabad,Islamabad,2.8,
10/3/2016 18:51,10/3/2016 19:01,Business,Islamabad,Islamabad,1.6,
10/3/2016 22:04,10/3/2016 22:33,Business,Islamabad,Unknown Location,12.7,
10/4/2016 9:50,10/4/2016 10:52,Business,Unknown Location,Unknown Location,28.6,
10/4/2016 12:17,10/4/2016 12:18,Business,Unknown Location,Unknown Location,15.1,
10/6/2016 8:49,10/6/2016 11:36,Business,Unknown Location,R?walpindi,17.9,
10/6/2016 17:23,10/6/2016 17:40,Business,R?walpindi,Unknown Location,112.6,
10/6/2016 18:37,10/6/2016 18:39,Business,Unknown Location,Unknown Location,18.4,
10/6/2016 19:46,10/6/2016 20:26,Business,Unknown Location,Unknown Location,13.8,
10/7/2016 10:56,10/7/2016 10:59,Business,Unknown Location,Lahore,33.2,
10/7/2016 11:27,10/7/2016 11:50,Business,Lahore,Lahore,2.6,
10/7/2016 13:52,10/7/2016 14:08,Business,Lahore,Unknown Location,5.8,
10/7/2016 14:29,10/7/2016 15:11,Business,Unknown Location,Lahore,8.3,
10/7/2016 15:47,10/7/2016 16:02,Business,Lahore,Lahore,2.4,
10/7/2016 18:08,10/7/2016 18:27,Business,Lahore,Lahore,3.1,
10/7/2016 18:33,10/7/2016 19:01,Business,Lahore,Lahore,6.1,
10/8/2016 15:03,10/8/2016 15:03,Business,Karachi,Karachi,3.6,
10/8/2016 18:15,10/8/2016 18:18,Business,Karachi,Unknown Location,8,
10/9/2016 14:04,10/9/2016 14:23,Business,Unknown Location,Unknown Location,7.7,Temporary Site
10/10/2016 17:22,10/10/2016 17:28,Business,Islamabad,Islamabad,1.7,
10/10/2016 17:33,10/10/2016 18:13,Business,Islamabad,Unknown Location,9.5,
10/11/2016 1:27,10/11/2016 2:08,Business,Unknown Location,R?walpindi,17.1,Meeting
10/12/2016 19:18,10/12/2016 19:21,Business,R?walpindi,Unknown Location,18.4,
10/13/2016 11:20,10/13/2016 11:58,Business,Unknown Location,Islamabad,9.8,
10/13/2016 12:08,10/13/2016 12:14,Business,Islamabad,Islamabad,1,
10/13/2016 13:02,10/13/2016 13:02,Business,Islamabad,Islamabad,0.7,
10/13/2016 13:37,10/13/2016 13:46,Business,Islamabad,Islamabad,2.3,
10/13/2016 16:08,10/13/2016 16:53,Business,Islamabad,Unknown Location,10.9,
10/14/2016 8:50,10/14/2016 9:44,Business,Unknown Location,R?walpindi,12.7,
10/14/2016 10:16,10/14/2016 10:52,Business,R?walpindi,Unknown Location,12.4,
10/14/2016 15:56,10/14/2016 16:20,Business,Unknown Location,Unknown Location,3.8,
10/14/2016 23:54,10/15/2016 2:06,Business,Unknown Location,R?walpindi,17,Meeting
10/15/2016 22:28,10/15/2016 22:48,Business,Morrisville,Morrisville,6.2,
10/16/2016 0:01,10/16/2016 0:14,Business,Morrisville,Cary,3.1,
10/16/2016 12:52,10/16/2016 13:11,Business,Cary,Durham,10.5,Meeting
10/16/2016 14:40,10/16/2016 15:01,Business,Durham,Morrisville,8.1,
10/16/2016 15:10,10/16/2016 15:19,Business,Morrisville,Cary,3.1,
10/16/2016 19:27,10/16/2016 19:33,Business,Whitebridge,Parkway,2.1,Meeting
10/16/2016 20:30,10/16/2016 20:39,Business,Cary,Morrisville,4.3,
10/16/2016 21:34,10/16/2016 21:41,Business,Morrisville,Cary,2.5,Meal/Entertain
10/17/2016 15:19,10/17/2016 15:57,Business,Cary,Raleigh,20.6,
10/17/2016 16:29,10/17/2016 17:11,Business,Raleigh,Cary,17.6,
10/17/2016 18:02,10/17/2016 18:16,Business,Cary,Apex,5.6,
10/17/2016 18:31,10/17/2016 18:45,Business,Apex,Apex,3.3,
10/17/2016 19:08,10/17/2016 19:25,Business,Apex,Cary,5.3,
10/18/2016 8:12,10/18/2016 8:22,Business,Whitebridge,Edgehill Farms,3.3,
10/18/2016 8:53,10/18/2016 9:02,Business,Edgehill Farms,Whitebridge,3.3,
10/18/2016 10:41,10/18/2016 11:09,Business,Cary,Morrisville,7.9,Temporary Site
10/18/2016 18:12,10/18/2016 18:33,Business,Oakland,Emeryville,13,
10/18/2016 19:03,10/18/2016 19:13,Business,Emeryville,Berkeley,3,
10/18/2016 20:31,10/18/2016 20:37,Business,Berkeley,Emeryville,3,
10/19/2016 9:33,10/19/2016 9:47,Business,Emeryville,Oakland,3.8,
10/19/2016 9:54,10/19/2016 10:21,Business,Oakland,San Francisco,9.5,
10/19/2016 13:45,10/19/2016 13:56,Business,SOMISSPO,French Quarter,1.7,
10/19/2016 14:02,10/19/2016 14:31,Business,San Francisco,Berkeley,10.8,
10/19/2016 15:44,10/19/2016 16:02,Business,West Berkeley,North Berkeley Hills,4.1,
10/19/2016 16:06,10/19/2016 16:19,Business,North Berkeley Hills,Southside,2.2,
10/19/2016 16:33,10/19/2016 17:01,Business,Berkeley,Emeryville,4.6,
10/20/2016 11:26,10/20/2016 11:34,Business,Emeryville,Berkeley,3.1,
10/20/2016 12:19,10/20/2016 13:17,Business,Berkeley,San Jose,47.7,
10/20/2016 20:44,10/20/2016 21:37,Business,San Jose,Emeryville,44.6,
10/21/2016 10:06,10/21/2016 10:21,Business,Emeryville,Oakland,13.2,
10/22/2016 0:54,10/22/2016 1:09,Business,Morrisville,Cary,8.7,
10/22/2016 13:26,10/22/2016 14:03,Business,Cary,Raleigh,17.2,
10/22/2016 17:08,10/22/2016 17:55,Business,Raleigh,Cary,14,
10/23/2016 9:24,10/23/2016 10:05,Business,Cary,Raleigh,28.1,
10/23/2016 12:17,10/23/2016 12:59,Business,Raleigh,Cary,28.2,
10/23/2016 19:04,10/23/2016 19:14,Business,Cary,Morrisville,3.1,Meal/Entertain
10/23/2016 21:10,10/23/2016 21:25,Business,Morrisville,Cary,3.1,Customer Visit
10/24/2016 14:57,10/24/2016 15:26,Business,Cary,Durham,16.4,
10/24/2016 15:33,10/24/2016 16:13,Business,Durham,Morrisville,15.4,
10/24/2016 16:34,10/24/2016 16:41,Business,Morrisville,Cary,2.2,
10/25/2016 13:27,10/25/2016 14:08,Business,Cary,Apex,11.2,
10/25/2016 15:04,10/25/2016 15:11,Business,Apex,Eagle Rock,2.2,
10/25/2016 15:16,10/25/2016 15:33,Business,Eagle Rock,Cary,3.6,
10/25/2016 20:00,10/25/2016 20:11,Business,Whitebridge,Savon Height,3.6,Meal/Entertain
10/25/2016 20:54,10/25/2016 21:03,Business,Savon Height,Parkway,4.9,
10/25/2016 22:24,10/25/2016 22:45,Business,Parkway,Whitebridge,8.7,Errand/Supplies
10/26/2016 19:25,10/26/2016 19:31,Business,Whitebridge,Parkway,2.1,Meeting
10/26/2016 20:53,10/26/2016 21:03,Business,Parkway,Whitebridge,2.1,
10/27/2016 18:51,10/27/2016 19:16,Business,Cary,Morrisville,8.4,Meeting
10/27/2016 19:20,10/27/2016 19:35,Business,Morrisville,Morrisville,5.9,
10/27/2016 19:52,10/27/2016 20:21,Business,Huntington Woods,Huntington Woods,12.1,
10/27/2016 20:47,10/27/2016 20:54,Business,Huntington Woods,Weston,3.9,
10/27/2016 21:26,10/27/2016 21:48,Business,Morrisville,Cary,6.2,
10/28/2016 11:34,10/28/2016 11:52,Business,Cary,Durham,10.4,Meeting
10/28/2016 13:06,10/28/2016 13:36,Business,Durham,Cary,9.9,Meeting
10/28/2016 15:53,10/28/2016 17:59,Business,Cary,Winston Salem,107,Meeting
10/28/2016 18:13,10/28/2016 20:07,Business,Winston Salem,Asheville,133.6,Meeting
10/28/2016 20:13,10/28/2016 22:00,Business,Asheville,Topton,91.8,Meeting
10/29/2016 15:22,10/29/2016 17:05,Business,Topton,Hayesville,40.7,Meeting
10/29/2016 17:13,10/29/2016 19:19,Business,Hayesville,Topton,75.7,
10/30/2016 7:49,10/30/2016 8:30,Business,Topton,Bryson City,29.8,
10/30/2016 9:07,10/30/2016 10:09,Business,Bryson City,Bryson City,16.3,
10/30/2016 10:11,10/30/2016 10:38,Business,Bryson City,Bryson City,6.5,
10/30/2016 10:51,10/30/2016 11:21,Business,Bryson City,Bryson City,6.3,
10/30/2016 12:24,10/30/2016 12:35,Business,Bryson City,Almond,6.6,
10/30/2016 12:58,10/30/2016 13:18,Business,Almond,Bryson City,15.2,
10/30/2016 13:24,10/30/2016 14:37,Business,Bryson City,Asheville,68.4,
10/30/2016 15:22,10/30/2016 18:23,Business,Asheville,Mebane,195.9,
10/30/2016 18:26,10/30/2016 19:39,Business,Mebane,Cary,45.2,
10/31/2016 18:11,10/31/2016 18:20,Business,Cary,Morrisville,3.2,
10/31/2016 18:47,10/31/2016 19:16,Business,Morrisville,Raleigh,10.3,
10/31/2016 20:18,10/31/2016 20:44,Business,Raleigh,Cary,13.1,
10/31/2016 21:45,10/31/2016 22:10,Business,Savon Height,Whitebridge,9.6,Errand/Supplies
11/1/2016 11:50,11/1/2016 12:27,Business,Cary,Durham,16.5,
11/1/2016 16:29,11/1/2016 17:02,Business,Durham,Cary,12.8,
11/1/2016 17:35,11/1/2016 17:42,Business,Whitebridge,Whitebridge,1.2,
11/1/2016 19:14,11/1/2016 19:20,Business,Whitebridge,Whitebridge,1,
11/1/2016 19:59,11/1/2016 20:12,Business,Whitebridge,Whitebridge,4.1,
11/1/2016 20:41,11/1/2016 20:55,Business,Whitebridge,Whitebridge,4.2,Meal/Entertain
11/2/2016 15:10,11/2/2016 15:18,Business,Whitebridge,Westpark Place,1.4,
11/2/2016 15:45,11/2/2016 15:52,Business,Westpark Place,Whitebridge,1.8,
11/2/2016 16:46,11/2/2016 17:11,Business,Cary,Morrisville,8.5,Meeting
11/2/2016 17:34,11/2/2016 17:49,Business,Morrisville,Morrisville,5,
11/2/2016 17:53,11/2/2016 18:00,Business,Morrisville,Cary,3.8,
11/3/2016 11:28,11/3/2016 11:34,Business,Whitebridge,Hazelwood,2.5,
11/3/2016 12:43,11/3/2016 12:49,Business,Hazelwood,Whitebridge,2.4,
11/3/2016 13:42,11/3/2016 13:47,Business,Whitebridge,Westpark Place,1.4,
11/3/2016 14:13,11/3/2016 14:26,Business,Westpark Place,Whitebridge,1.8,
11/3/2016 18:51,11/3/2016 19:08,Business,Cary,Morrisville,3.1,Meal/Entertain
11/3/2016 22:46,11/3/2016 22:58,Business,Morrisville,Cary,3.1,Customer Visit
11/4/2016 10:02,11/4/2016 10:18,Business,Cary,Morrisville,7.9,Temporary Site
11/4/2016 18:14,11/4/2016 18:21,Business,San Jose,Santa Clara,3.8,
11/4/2016 21:04,11/4/2016 21:20,Business,Agnew,Cory,4.3,
11/4/2016 22:12,11/4/2016 22:25,Business,Cory,Agnew,3.9,
11/5/2016 8:34,11/5/2016 8:43,Business,Agnew,Renaissance,2.2,
11/5/2016 17:29,11/5/2016 17:40,Business,Renaissance,Agnew,2.8,
11/5/2016 19:20,11/5/2016 19:28,Business,Agnew,Agnew,2.2,
11/6/2016 10:50,11/6/2016 11:04,Business,Agnew,Renaissance,2.4,
11/6/2016 16:05,11/6/2016 16:22,Business,Renaissance,Agnew,2.8,Meeting
11/6/2016 16:27,11/6/2016 17:28,Business,Santa Clara,Berkeley,43.9,Customer Visit
11/6/2016 19:04,11/6/2016 19:12,Business,Downtown,West Berkeley,1.8,
11/6/2016 20:06,11/6/2016 20:21,Business,West Berkeley,Central,3.3,
11/7/2016 12:28,11/7/2016 12:57,Business,Berkeley,San Francisco,11.8,Between Offices
11/7/2016 19:17,11/7/2016 19:57,Business,San Francisco,Berkeley,13.2,Between Offices
11/8/2016 10:29,11/8/2016 10:57,Business,Berkeley,San Francisco,12.2,Between Offices
11/8/2016 12:16,11/8/2016 12:49,Business,San Francisco,Berkeley,11.3,Meeting
11/8/2016 13:41,11/8/2016 14:01,Business,Berkeley,Emeryville,3.6,
11/8/2016 16:21,11/8/2016 16:34,Business,Emeryville,Berkeley,3,
11/9/2016 13:08,11/9/2016 13:41,Business,Berkeley,San Francisco,11.4,
11/9/2016 15:58,11/9/2016 16:04,Business,NOMA,Downtown,0.9,
11/9/2016 17:31,11/9/2016 18:03,Business,Downtown,Sunnyside,6.2,
11/9/2016 18:09,11/9/2016 18:14,Business,Sunnyside,Ingleside,0.7,
11/9/2016 18:21,11/9/2016 18:35,Business,Ingleside,Potrero Flats,5.5,Meeting
11/9/2016 18:40,11/9/2016 19:17,Business,San Francisco,Oakland,12.7,Customer Visit
11/9/2016 20:52,11/9/2016 21:02,Business,Oakland,Berkeley,2.6,
11/9/2016 21:56,11/9/2016 22:02,Business,Central,Central,1.1,
11/10/2016 9:46,11/10/2016 10:15,Business,Berkeley,San Francisco,12.6,Temporary Site
11/10/2016 10:20,11/10/2016 10:31,Business,Tenderloin,SOMISSPO,1.2,
11/10/2016 14:57,11/10/2016 15:07,Business,SOMISSPO,Tenderloin,1.1,
11/10/2016 15:17,11/10/2016 15:22,Business,San Francisco,Oakland,9.9,Temporary Site
11/10/2016 15:30,11/10/2016 15:53,Business,Oakland,Berkeley,6,Meeting
11/10/2016 19:18,11/10/2016 19:21,Business,West Berkeley,Central,0.8,
11/11/2016 9:35,11/11/2016 10:23,Business,Berkeley,Menlo Park,45.9,Customer Visit
11/11/2016 12:58,11/11/2016 13:13,Business,Menlo Park,Palo Alto,4,
11/11/2016 14:20,11/11/2016 14:32,Business,Palo Alto,Menlo Park,2.5,
11/11/2016 14:39,11/11/2016 15:46,Business,Menlo Park,Berkeley,36.6,Customer Visit
11/11/2016 18:30,11/11/2016 18:43,Business,Central,College Avenue,2.9,
11/11/2016 21:08,11/11/2016 21:18,Business,College Avenue,Central,2.6,
11/12/2016 10:32,11/12/2016 10:52,Business,Central,South,2.3,
11/12/2016 10:55,11/12/2016 11:25,Business,South,Downtown,6.4,
11/12/2016 13:07,11/12/2016 13:15,Business,Downtown,Central,1.4,
11/12/2016 13:46,11/12/2016 13:50,Business,Central,West Berkeley,0.6,
11/12/2016 14:22,11/12/2016 14:53,Business,West Berkeley,South,5.9,Meeting
11/12/2016 15:14,11/12/2016 15:21,Business,South,Southwest Berkeley,0.8,
11/12/2016 15:25,11/12/2016 15:36,Business,Berkeley,Emeryville,1.3,
11/12/2016 15:40,11/12/2016 15:59,Business,Emeryville,Berkeley,3.7,Errand/Supplies
11/13/2016 8:54,11/13/2016 9:02,Business,Central,Central,2.3,
11/13/2016 9:27,11/13/2016 9:53,Business,Central,Central,2.6,
11/13/2016 10:31,11/13/2016 10:37,Business,Central,Southside,1.9,
11/13/2016 11:04,11/13/2016 11:16,Business,Southside,West Berkeley,2.1,
11/13/2016 12:22,11/13/2016 12:51,Business,West Berkeley,Southside,4,Meeting
11/13/2016 13:05,11/13/2016 13:11,Business,Southside,South Berkeley,0.9,
11/13/2016 13:14,11/13/2016 13:18,Business,South Berkeley,Southside,0.9,
11/13/2016 14:35,11/13/2016 14:46,Business,Southside,Central,2.4,
11/13/2016 15:14,11/13/2016 15:24,Business,Central,Southside,1.9,
11/13/2016 15:47,11/13/2016 15:59,Business,Southside,Central,1.9,
11/14/2016 11:24,11/14/2016 12:13,Business,Berkeley,Mountain View,44.6,Customer Visit
11/14/2016 13:40,11/14/2016 14:33,Business,Mountain View,Berkeley,43.6,Customer Visit
11/14/2016 15:27,11/14/2016 15:36,Business,Berkeley,Emeryville,2.5,
11/14/2016 20:19,11/14/2016 20:30,Business,Emeryville,Berkeley,3.7,Errand/Supplies
11/15/2016 13:59,11/15/2016 14:06,Business,Berkeley,Oakland,5.1,
11/15/2016 14:09,11/15/2016 14:26,Business,Oakland,San Francisco,9.7,Temporary Site
11/15/2016 20:44,11/15/2016 21:00,Business,San Francisco,Berkeley,11.8,Temporary Site
11/16/2016 20:21,11/16/2016 20:27,Business,Berkeley,El Cerrito,2.3,Temporary Site
11/16/2016 22:52,11/16/2016 23:02,Business,El Cerrito,Berkeley,3.1,Meal/Entertain
11/17/2016 10:13,11/17/2016 10:44,Business,Berkeley,Oakland,16.3,Customer Visit
11/18/2016 20:09,11/18/2016 20:19,Business,Cary,Morrisville,3.1,Meal/Entertain
11/18/2016 21:23,11/18/2016 21:34,Business,Morrisville,Cary,5.2,Meal/Entertain
11/18/2016 21:56,11/18/2016 22:21,Business,Krendle Woods,Whitebridge,6.1,Meeting
11/19/2016 13:51,11/19/2016 14:10,Business,Cary,Durham,10.3,Meeting
11/19/2016 14:30,11/19/2016 14:51,Business,Durham,Cary,10.5,Meeting
11/19/2016 16:01,11/19/2016 16:06,Business,Cary,Cary,1.5,
11/19/2016 16:27,11/19/2016 16:41,Business,Cary,Cary,1.8,
11/19/2016 17:41,11/19/2016 17:54,Business,Cary,Apex,5.4,Errand/Supplies
11/19/2016 21:14,11/19/2016 21:35,Business,Apex,Cary,5.4,Customer Visit
11/20/2016 10:27,11/20/2016 11:32,Business,Cary,Cary,39.2,Between Offices
11/20/2016 11:58,11/20/2016 12:28,Business,Cary,Cary,6.4,Customer Visit
11/20/2016 14:58,11/20/2016 15:07,Business,Cary,Cary,2.7,Meeting
11/20/2016 17:45,11/20/2016 18:37,Business,Cary,Cary,18.5,Errand/Supplies
11/21/2016 13:37,11/21/2016 13:49,Business,Cary,Cary,2.5,Meal/Entertain
11/21/2016 14:34,11/21/2016 14:44,Business,Cary,Cary,2.1,Meal/Entertain
11/21/2016 17:50,11/21/2016 18:04,Business,Cary,Unknown Location,6.7,Errand/Supplies
11/21/2016 18:18,11/21/2016 18:27,Business,Unknown Location,Morrisville,3.5,Meal/Entertain
11/21/2016 18:43,11/21/2016 18:51,Business,Morrisville,Cary,3.4,Errand/Supplies
11/22/2016 15:12,11/22/2016 15:27,Business,Cary,Cary,5.5,Meeting
11/22/2016 15:31,11/22/2016 15:44,Business,Cary,Cary,4.1,Meeting
11/22/2016 15:51,11/22/2016 16:43,Business,Cary,Cary,12.7,Customer Visit
11/22/2016 18:18,11/22/2016 18:28,Business,Cary,Morrisville,3,Meal/Entertain
11/22/2016 21:02,11/22/2016 21:14,Business,Morrisville,Cary,3.5,Customer Visit
11/23/2016 15:34,11/23/2016 15:50,Business,Cary,Cary,5.9,Meal/Entertain
11/23/2016 16:18,11/23/2016 16:29,Business,Cary,Cary,1.9,
11/23/2016 16:49,11/23/2016 17:00,Business,Cary,Cary,3.3,
11/23/2016 18:37,11/23/2016 18:47,Business,Cary,Cary,1.3,
11/25/2016 11:47,11/25/2016 12:04,Business,Cary,Durham,10.3,Meeting
11/25/2016 13:13,11/25/2016 13:31,Business,Durham,Cary,11.1,Meeting
11/26/2016 15:54,11/26/2016 15:59,Business,Cary,Cary,1.4,
11/26/2016 17:00,11/26/2016 17:12,Business,Cary,Apex,5.1,Meeting
11/26/2016 17:36,11/26/2016 17:56,Business,Apex,Holly Springs,9,Meeting
11/26/2016 18:29,11/26/2016 19:04,Business,Holly Springs,Cary,13.3,Between Offices
11/26/2016 19:47,11/26/2016 19:54,Business,Cary,Cary,2.5,Errand/Supplies
11/27/2016 15:59,11/27/2016 16:06,Business,Cary,Morrisville,3.3,Meal/Entertain
11/27/2016 18:55,11/27/2016 19:09,Business,Morrisville,Cary,2.9,
11/30/2016 11:03,11/30/2016 11:34,Business,Cary,Raleigh,8.5,Customer Visit
11/30/2016 11:53,11/30/2016 12:35,Business,Raleigh,Morrisville,6.7,Temporary Site
11/30/2016 12:43,11/30/2016 12:53,Business,Morrisville,Cary,3.1,
12/1/2016 7:44,12/1/2016 7:59,Business,Cary,Cary,5.5,Meeting
12/1/2016 8:37,12/1/2016 8:53,Business,Cary,Cary,5.5,Errand/Supplies
12/1/2016 18:00,12/1/2016 18:12,Business,Cary,Morrisville,2.9,Meal/Entertain
12/1/2016 20:36,12/1/2016 20:46,Business,Morrisville,Cary,2.9,Customer Visit
12/2/2016 12:12,12/2/2016 12:23,Business,Cary,Apex,5.1,Meal/Entertain
12/2/2016 13:07,12/2/2016 13:22,Business,Apex,Cary,5.3,Customer Visit
12/2/2016 20:41,12/2/2016 20:48,Business,Cary,Morrisville,3.3,Meal/Entertain
12/2/2016 22:59,12/2/2016 23:07,Business,Morrisville,Cary,3,Customer Visit
12/3/2016 18:35,12/3/2016 18:56,Business,Cary,Wake Co.,6.6,Errand/Supplies
12/3/2016 19:08,12/3/2016 19:15,Business,Wake Co.,Morrisville,1.8,
12/3/2016 20:31,12/3/2016 20:41,Business,Morrisville,Cary,3,Customer Visit
12/4/2016 18:56,12/4/2016 19:03,Business,Cary,Morrisville,2.9,Meal/Entertain
12/4/2016 20:23,12/4/2016 20:34,Business,Morrisville,Cary,3.4,Customer Visit
12/5/2016 18:04,12/5/2016 18:17,Business,Cary,Cary,4.1,
12/5/2016 19:22,12/5/2016 19:37,Business,Cary,Cary,3.8,Meal/Entertain
12/7/2016 12:03,12/7/2016 12:32,Business,Cary,Cary,6.6,Meeting
12/7/2016 12:35,12/7/2016 12:46,Business,Cary,Cary,4,Meeting
12/7/2016 19:53,12/7/2016 20:13,Business,Cary,Cary,7,Customer Visit
12/7/2016 21:13,12/7/2016 21:50,Business,Cary,Cary,6.9,Meal/Entertain
12/8/2016 14:19,12/8/2016 14:32,Business,Cary,Cary,3.4,Errand/Supplies
12/8/2016 14:53,12/8/2016 15:02,Business,Cary,Cary,3.4,Errand/Supplies
12/8/2016 19:22,12/8/2016 19:27,Business,Cary,Cary,2,Meeting
12/8/2016 21:26,12/8/2016 21:31,Business,Cary,Cary,2,Errand/Supplies
12/9/2016 12:09,12/9/2016 12:24,Business,Cary,Apex,5.1,Errand/Supplies
12/9/2016 13:15,12/9/2016 13:43,Business,Apex,Cary,8.8,Temporary Site
12/9/2016 20:11,12/9/2016 20:34,Business,Cary,Cary,5.6,Meeting
12/9/2016 22:03,12/9/2016 22:57,Business,Cary,Cary,18.9,Customer Visit
12/10/2016 12:43,12/10/2016 13:16,Business,Cary,Fuquay-Varina,15.6,Meeting
12/10/2016 14:42,12/10/2016 15:18,Business,Fuquay-Varina,Cary,15.6,Errand/Supplies
12/10/2016 18:17,12/10/2016 18:27,Business,Cary,Morrisville,3,Meal/Entertain
12/10/2016 22:09,12/10/2016 22:21,Business,Morrisville,Cary,3.1,Customer Visit
12/11/2016 16:06,12/11/2016 16:16,Business,Cary,Morrisville,3,Meal/Entertain
12/11/2016 19:05,12/11/2016 19:15,Business,Morrisville,Cary,4.8,Errand/Supplies
12/11/2016 21:48,12/11/2016 21:56,Business,Cary,Cary,2.1,Errand/Supplies
12/12/2016 13:22,12/12/2016 13:32,Business,Cary,Cary,3.1,Errand/Supplies
12/12/2016 13:36,12/12/2016 13:51,Business,Cary,Apex,4.4,Meal/Entertain
12/12/2016 14:26,12/12/2016 14:39,Business,Apex,Cary,4.7,Customer Visit
12/12/2016 17:51,12/12/2016 18:01,Business,Cary,Morrisville,3,Meal/Entertain
12/12/2016 20:48,12/12/2016 20:57,Business,Morrisville,Cary,3,Customer Visit
12/13/2016 18:19,12/13/2016 18:29,Business,Cary,Cary,4.2,Errand/Supplies
12/13/2016 20:20,12/13/2016 20:29,Business,Cary,Cary,4.1,Meal/Entertain
12/14/2016 16:52,12/14/2016 17:10,Business,Cary,Cary,3.4,
12/14/2016 17:22,12/14/2016 17:34,Business,Cary,Cary,3.3,
12/14/2016 17:50,12/14/2016 18:00,Business,Cary,Morrisville,3,Meal/Entertain
12/14/2016 20:24,12/14/2016 20:40,Business,Morrisville,Cary,3.1,Customer Visit
12/15/2016 14:20,12/15/2016 14:54,Business,Cary,Morrisville,10.6,Meeting
12/17/2016 15:38,12/17/2016 16:12,Business,Unknown Location,Unknown Location,4.8,Airport/Travel
12/17/2016 17:19,12/17/2016 17:59,Business,Unknown Location,Unknown Location,5.3,Temporary Site
12/18/2016 13:03,12/18/2016 13:41,Business,Unknown Location,Unknown Location,4.9,Errand/Supplies
12/18/2016 16:38,12/18/2016 17:25,Business,Unknown Location,Unknown Location,10.2,Errand/Supplies
12/18/2016 20:35,12/18/2016 21:04,Business,Unknown Location,Unknown Location,9.2,
12/19/2016 9:08,12/19/2016 9:36,Business,Unknown Location,Islamabad,7.7,Errand/Supplies
12/19/2016 10:15,12/19/2016 10:34,Business,Islamabad,Rawalpindi,5.9,Temporary Site
12/19/2016 13:04,12/19/2016 13:08,Business,Rawalpindi,Unknown Location,0.7,Errand/Supplies
12/19/2016 13:24,12/19/2016 13:35,Business,Unknown Location,Unknown Location,1.3,
12/19/2016 14:07,12/19/2016 14:15,Business,Unknown Location,Unknown Location,2.5,
12/19/2016 14:18,12/19/2016 14:32,Business,Unknown Location,Unknown Location,5.3,
12/19/2016 14:37,12/19/2016 14:50,Business,Unknown Location,Unknown Location,5.4,
12/19/2016 15:09,12/19/2016 15:38,Business,Unknown Location,Rawalpindi,10.2,Customer Visit
12/19/2016 16:50,12/19/2016 17:09,Business,Rawalpindi,Islamabad,7.2,Customer Visit
12/19/2016 19:05,12/19/2016 19:17,Business,Islamabad,Unknown Location,2.2,
12/19/2016 19:55,12/19/2016 20:30,Business,Unknown Location,Unknown Location,11,Meeting
12/20/2016 8:49,12/20/2016 9:24,Business,Unknown Location,Rawalpindi,12,
12/20/2016 10:30,12/20/2016 10:48,Business,Rawalpindi,Rawalpindi,3.3,Errand/Supplies
12/20/2016 11:30,12/20/2016 12:17,Business,Rawalpindi,Unknown Location,19.4,Meeting
12/20/2016 13:14,12/20/2016 13:20,Business,Unknown Location,Unknown Location,1.7,Errand/Supplies
12/20/2016 13:54,12/20/2016 14:17,Business,Unknown Location,Islamabad,5.7,Temporary Site
12/20/2016 16:14,12/20/2016 16:24,Business,Islamabad,Islamabad,1.8,Errand/Supplies
12/20/2016 16:56,12/20/2016 17:07,Business,Islamabad,Islamabad,1.4,Errand/Supplies
12/20/2016 18:47,12/20/2016 19:21,Business,Islamabad,Unknown Location,10.3,Customer Visit
12/21/2016 7:42,12/21/2016 8:10,Business,Unknown Location,Unknown Location,11.5,Meeting
12/21/2016 10:14,12/21/2016 10:30,Business,Unknown Location,Islamabad,4.9,Errand/Supplies
12/21/2016 11:35,12/21/2016 11:49,Business,Islamabad,Unknown Location,3.5,Meal/Entertain
12/21/2016 12:51,12/21/2016 13:33,Business,Unknown Location,Unknown Location,16.2,Meeting
12/21/2016 15:38,12/21/2016 15:49,Business,Unknown Location,Unknown Location,2,Errand/Supplies
12/21/2016 15:55,12/21/2016 16:05,Business,Unknown Location,Islamabad,2.1,Errand/Supplies
12/21/2016 17:45,12/21/2016 17:54,Business,Islamabad,Islamabad,2.1,Meeting
12/21/2016 17:59,12/21/2016 18:31,Business,Islamabad,Unknown Location,7.2,Customer Visit
12/21/2016 19:49,12/21/2016 20:35,Business,Unknown Location,Rawalpindi,12,Meeting
12/21/2016 20:56,12/21/2016 23:42,Business,Rawalpindi,Unknown Location,103,Meeting
12/22/2016 15:40,12/22/2016 16:38,Business,Unknown Location,Unknown Location,32.3,Meeting
12/22/2016 17:04,12/22/2016 17:20,Business,Unknown Location,Unknown Location,5.3,Customer Visit
12/22/2016 17:27,12/22/2016 17:53,Business,Unknown Location,Unknown Location,11.6,Meeting
12/22/2016 17:56,12/22/2016 18:29,Business,Unknown Location,Unknown Location,23.2,Meeting
12/22/2016 18:31,12/22/2016 18:37,Business,Unknown Location,Unknown Location,3.2,Errand/Supplies
12/22/2016 18:38,12/22/2016 18:47,Business,Unknown Location,Unknown Location,12.3,Temporary Site
12/22/2016 19:04,12/22/2016 19:50,Business,Unknown Location,Lahore,14,Meeting
12/22/2016 21:41,12/22/2016 21:53,Business,Lahore,Lahore,2.1,Meal/Entertain
12/22/2016 23:27,12/22/2016 23:32,Business,Lahore,Lahore,2.1,Customer Visit
12/23/2016 9:21,12/23/2016 9:41,Business,Lahore,Lahore,3,Meeting
12/23/2016 11:33,12/23/2016 11:58,Business,Lahore,Unknown Location,6.2,Meeting
12/23/2016 14:15,12/23/2016 15:25,Business,Unknown Location,Unknown Location,9.6,Meeting
12/23/2016 16:23,12/23/2016 16:34,Business,Unknown Location,Unknown Location,1.3,Errand/Supplies
12/23/2016 17:34,12/23/2016 18:27,Business,Unknown Location,Lahore,7.1,Meal/Entertain
12/24/2016 7:43,12/24/2016 8:04,Business,Lahore,Unknown Location,6.3,Meal/Entertain
12/24/2016 9:19,12/24/2016 9:55,Business,Unknown Location,Lahore,10.7,Meal/Entertain
12/24/2016 10:34,12/24/2016 10:53,Business,Lahore,Lahore,5.3,Meal/Entertain
12/24/2016 12:51,12/24/2016 12:53,Business,Lahore,Lahore,1.6,Errand/Supplies
12/24/2016 13:08,12/24/2016 13:29,Business,Lahore,Lahore,3.6,Errand/Supplies
12/24/2016 17:12,12/24/2016 17:27,Business,Lahore,Lahore,1.7,Errand/Supplies
12/24/2016 19:12,12/24/2016 19:27,Business,Lahore,Lahore,2.9,Meal/Entertain
12/24/2016 22:04,12/24/2016 22:09,Business,Lahore,Lahore,0.6,Errand/Supplies
12/25/2016 0:10,12/25/2016 0:14,Business,Lahore,Lahore,0.6,Errand/Supplies
12/25/2016 19:15,12/25/2016 19:26,Business,Lahore,Lahore,2.3,Meal/Entertain
12/25/2016 21:58,12/25/2016 22:04,Business,Lahore,Lahore,2.3,Meal/Entertain
12/26/2016 8:30,12/26/2016 8:41,Business,Lahore,Lahore,3.2,Meal/Entertain
12/26/2016 9:05,12/26/2016 9:19,Business,Lahore,Lahore,6.2,Customer Visit
12/26/2016 10:15,12/26/2016 10:36,Business,Lahore,Lahore,7.7,Customer Visit
12/26/2016 11:29,12/26/2016 11:42,Business,Lahore,Lahore,3.8,Customer Visit
12/26/2016 13:09,12/26/2016 13:43,Business,Lahore,Unknown Location,7.9,Meeting
12/27/2016 7:02,12/27/2016 7:14,Business,Kar?chi,Kar?chi,4.9,Temporary Site
12/27/2016 8:37,12/27/2016 8:59,Business,Kar?chi,Kar?chi,5,Meal/Entertain
12/27/2016 12:53,12/27/2016 12:57,Business,Kar?chi,Kar?chi,0.6,Meal/Entertain
12/27/2016 14:49,12/27/2016 15:03,Business,Kar?chi,Unknown Location,3.1,Customer Visit
12/27/2016 16:34,12/27/2016 16:58,Business,Unknown Location,Kar?chi,7.9,Meeting
12/27/2016 19:19,12/27/2016 19:50,Business,Kar?chi,Kar?chi,5.5,Customer Visit
12/28/2016 8:34,12/28/2016 9:06,Business,Kar?chi,Unknown Location,10.3,Meal/Entertain
12/28/2016 11:42,12/28/2016 12:12,Business,Unknown Location,Kar?chi,10.4,Errand/Supplies
12/28/2016 13:53,12/28/2016 14:01,Business,Kar?chi,Kar?chi,2,Errand/Supplies
12/28/2016 15:04,12/28/2016 15:39,Business,Kar?chi,Unknown Location,8.5,Meal/Entertain
12/28/2016 17:02,12/28/2016 17:16,Business,Unknown Location,Kar?chi,4.4,Errand/Supplies
12/28/2016 18:33,12/28/2016 18:56,Business,Kar?chi,Kar?chi,3.8,Errand/Supplies
12/28/2016 22:44,12/28/2016 23:18,Business,Kar?chi,Kar?chi,5.1,Errand/Supplies
12/29/2016 0:49,12/29/2016 1:06,Business,Kar?chi,Kar?chi,3.8,Errand/Supplies
12/29/2016 9:44,12/29/2016 10:07,Business,Kar?chi,Unknown Location,11.6,Meal/Entertain
12/29/2016 11:28,12/29/2016 12:00,Business,Unknown Location,Kar?chi,11.9,Meal/Entertain
12/29/2016 12:25,12/29/2016 12:33,Business,Kar?chi,Kar?chi,1.4,Errand/Supplies
12/29/2016 13:17,12/29/2016 13:24,Business,Kar?chi,Kar?chi,1.1,Errand/Supplies
12/29/2016 13:56,12/29/2016 14:11,Business,Kar?chi,Kar?chi,4.1,Airport/Travel
12/29/2016 14:42,12/29/2016 14:58,Business,Kar?chi,Kar?chi,6.1,Between Offices
12/29/2016 15:05,12/29/2016 15:16,Business,Kar?chi,Kar?chi,1.3,Errand/Supplies
12/29/2016 18:59,12/29/2016 19:14,Business,Kar?chi,Unknown Location,3,Meal/Entertain
12/29/2016 19:50,12/29/2016 20:10,Business,Unknown Location,Kar?chi,4.1,Customer Visit
12/29/2016 20:15,12/29/2016 20:45,Business,Kar?chi,Kar?chi,7.2,Meeting
12/29/2016 20:53,12/29/2016 21:42,Business,Kar?chi,Unknown Location,6.4,
12/29/2016 23:14,12/29/2016 23:47,Business,Unknown Location,Kar?chi,12.9,Meeting
12/30/2016 10:15,12/30/2016 10:33,Business,Kar?chi,Kar?chi,2.8,Errand/Supplies
12/30/2016 11:31,12/30/2016 11:56,Business,Kar?chi,Kar?chi,2.9,Errand/Supplies
12/30/2016 15:41,12/30/2016 16:03,Business,Kar?chi,Kar?chi,4.6,Errand/Supplies
12/30/2016 16:45,12/30/2016 17:08,Business,Kar?chi,Kar?chi,4.6,Meeting
12/30/2016 23:06,12/30/2016 23:10,Business,Kar?chi,Kar?chi,0.8,Customer Visit
12/31/2016 1:07,12/31/2016 1:14,Business,Kar?chi,Kar?chi,0.7,Meeting
12/31/2016 13:24,12/31/2016 13:42,Business,Kar?chi,Unknown Location,3.9,Temporary Site
12/31/2016 15:03,12/31/2016 15:38,Business,Unknown Location,Unknown Location,16.2,Meeting
12/31/2016 21:32,12/31/2016 21:50,Business,Katunayake,Gampaha,6.4,Temporary Site
12/31/2016 22:08,12/31/2016 23:51,Business,Gampaha,Ilukwatta,48.2,Temporary Site
Totals,,,,,12204.7,
