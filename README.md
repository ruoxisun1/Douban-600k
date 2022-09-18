# Douban-600k

SUMMARY
================================================================================

These files contain 675,102 ratings of 50,671 movies 
made by 1,000 Douban Movie users.



RATINGS FILE DESCRIPTION
================================================================================

All data related to ratings are contained in the file "ratings.csv" and are in the
following format:

UserID::MovieID::MovieTags::Rating::RatingTime::ReviewLength::HelpfulVote

- UserIDs range between 1 and 1000
- MovieIDs range between 1 and 50671
- MovieTags are tags officially provided by the Douban Movie, represent in Chinese
- Ratings are made on a 5-star scale (whole-star ratings only)
- RatingTime is the time that rating is given, represented in yyyy-mm-dd 
- ReviewLength is the word count of the review given by user
- HelpfulVote is the helpful vote number of the review given by other users of Douban Movie

RATINGS FILE DESCRIPTION (PROCESSED)
================================================================================

All  data related to ratings are contained in the file "ratings.csv" which is pre-cleaned are in the
following format:

UserID::MovieID::MovieTags::Rating::RatingTime::ReviewLength::HelpfulVote

- UserIDs range between 1 and 1000
- MovieIDs range between 1 and 50671
- MovieTags are tags officially provided by the Douban Movie, covered to pinyin
- Ratings are made on a 5-star scale (whole-star ratings only)
- RatingTime is the time that rating is given, represented in yyyy-mm-dd 
- ReviewLength is the word count of the review given by user
- HelpfulVote is the helpful vote number of the review given by other users of Douban Movie cleaned to Arabic numerals only

USERS FILE DESCRIPTION
================================================================================

User information is in the file "users.csv" and is in the following
format:

UserID::UserPageLink::FollowerNumberCount

- UserIDs range between 1 and 1000
- UserPageLink is the link to the user's personal home page 
- FollowerNumberCount is the user’s follower number count


EXPLICIT TRUST RELATION DESCRIPTION
================================================================================

Existing trust relations is in the file "ExplictTrustRelation.csv" and is in the following
format:

LinkofFollowerUser::LinkofFollowedUser

- LinkofFollowerUser is the web page link for the user follower list
- LinkofFollowedUser is the web page link to the followed user's personal home page 




CITATION
================================================================================

To acknowledge use of the dataset in publications, please cite the following
paper:





