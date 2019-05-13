# Club Mahindra DataOlympics

_**Predict average spend on Food & Beverages by a Club Mahindra member from the dataset provided.**_

**Dataset Details**

- _train.csv_      -> Training Set ([Here](https://drive.google.com/open?id=1oqDhw3BYGl4ifITr15k7FIoPOMXgkmHk))
- _test.csv_       -> Test Set ([Here](https://drive.google.com/open?id=1b2HpSbtu-qS4t5eS32psZQtyJp15L65w))
- _sample_submission.csv_ -> File Submission Format ([Here](https://drive.google.com/open?id=1tl3xHcJQxLr_qiESUA1ilT_C6OkGczUI))

**Data Variables Description**

- `reservation_id`                      -> Reservation ID
- `booking_date`                        -> Date of booking
- `checkin_date`                        -> Checkin date recorded at the time of booking
- `checkout_date`                       -> Checkout date recorded at the time of booking
- `channel_code`                        -> Different channels of booking
- `main_product_code`                   -> Type of product a member has purchased
- `numberofadults`                      -> Number of adults travelling
- `numberofchildren`                    -> Number of children travelling
- `persontravellingid`                  -> Type of person travelling
- `resort_region_code`                  -> Resort Region
- `resort_type_code`                    -> Resort Type
- `room_type_booked_code`               -> Room Type
- `roomnights`                          -> Number of roomnights booked
- `season_holidayed_code`               -> Season Holidayed
- `state_code_residence`                -> Residence State of Member
- `state_code_resort`                   -> State in which resort is located
- `total_pax`                           -> Total persons travelling
- `member_age_buckets`                  -> Age bucket of the member
- `booking_type_code`                   -> Type of Booking
- `memberid`                            -> Unique ID of the member
- `cluster_code`                        -> Cluster Code of Resort
- `reservationstatusid_code`            -> Reservation Status ID
- `resort_id`                           -> Unique Resort ID
- `amount_spent_per_room_night_scaled`  -> _(Target)_ Resort Spend Per Room Night


**Libraries used** are `pandas`, `numpy` and `sklearn`. Also, `CatBoostRegressor` is trained on the training set after some analysis and preprocessing. The code is written in Google Colaboratory and thus, contains some of its commands which should be omitted if running on the local machine.

- Download the notebook `Mahindra-DataOlympics.ipynb`.
- Download the dataset from links above in same folder as that of notebook.
- Run all the cells in `Mahindra-DataOlympics.ipynb`.

P.S. - Play around with the hyperparameters of the model to achieve a further accuracy.
