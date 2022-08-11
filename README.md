# TDS_Project-2

FILES:


- ratings.csv  contains ratings sorted by time.Ratings go from one to five. Both book IDs and user IDs are contiguous. For books, they are 1-10000, for users, 1-53424.
- to_read.csv provides IDs of the books marked "to read" by each user, as user_id,book_id pairs, sorted by time.
- books.csv has metadata for each book (goodreads IDs, authors, title, average rating, etc.). The metadata has been extracted from goodreads XML files.
- book_tags.csv contains tags/shelves/genres assigned by users to books. Tags in this file are represented by their IDs. Each book_id  has multiple tag_id.The field "count" denotes ‘user records’ (the number of users tagged the given tag_id with the goodreads_book_id)

QUESTIONS :


1) How many books do not have an original title [books.csv] ? 
2) How many unique books are present in the dataset ? Evaluate based on the 'book_id' [books.csv]  
3) How many unique users are present in the dataset [ratings.csv] ? 
4) Which book (title) has the maximum number of ratings based on ‘work_ratings_count’  [books.csv] ? 
5) Which tag_id  is the most frequently used ie. mapped with the highest number of books [book_tags.csv]  ? (In case of more than one tag, mention the tag id with the least numerical value) 
6) Which book (title) has the most number of counts of tags given by the user [book_tags.csv,books.csv]  ? 
7) Which book (goodreads_book_id) is marked as to-read by most users [books.csv,toread.csv] ? 
8) Which is the least used tag, i.e. mapped with the lowest number of books [book_tags.csv]   ? (In case of more than one tag, mention the tag id with the least numerical value)  
9) Which book (title) has the minimum ‘average_rating’  [books.csv] ? 
10) Which book (goodreads_book_id) has the least number of count of tags given by the user  [book_tags.csv,books.csv] ? 
11) How many tags are there in the dataset [book_tags.csv]  ? 
12) What is the average rating of all the books in the dataset based on ‘average_rating’  [books.csv]  ? 
13) Find the number of books published in the year ‘2000’ based on the ‘original_publication_year’ [books.csv] ? 
14) Predict sentiment using Textblob. How many positive titles (title) are there [books.csv] ? (cut-off >0) 
15) Plot a bar chart in Flourish with top 20 unique tags  in descending order of ‘user records’ (the number of users tagged the given tag_id with the goodreads_book_id) [book_tags.csv] and share the published link.
16) Bucket the average_rating of books into 6 buckets [0,1,2,3,4,5] with 0.5 decimal rounding (eg: average_rating 3.5 to 4.4 will fall in bucket 4). Plot bar graph in Flourish to show total number of books in each rating bucket. [books.csv] and share the published link.
