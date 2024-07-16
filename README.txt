## explanation for variables in ads

label: int - Click-through label (0, 1)\
user_id: string - User ID\
age: string - Age group (e.g., 1, 2, 3...)\
gender: string - Gender (e.g., 1, 2)\
residence: string - Permanent residence (province)\
city: string - Permanent residence (city ID)\
city_rank: string - Permanent residence (city level)\
series_dev: string - Device series\
series_group: string - Device series group\
emui_dev: string - EMUI version number\
device_name: string - Device model\
device_size: string - Device size\
net_type: string - Network type\
task_id: string - Advertisement task ID\
adv_id: string - Advertisement material ID\
creat_type_cd: string - Creative type ID of the material\
adv_prim_id: string - Advertiser ID\
inter_type_cd: string - Interaction type ID of the material\
slot_id: string - Ad slot ID\
site_id: string - Media ID\
spread_app_id: string - Application ID for the advertisement\
hispace_app_tags: string - Tags for the advertisement application\
app_second_class: string - Secondary classification of the advertisement application\
app_score: int - Application score\
ad_click_list_v001: [string,] - List of advertisement task IDs clicked by the user\
ad_click_list_v002: [string,] - List of advertiser IDs clicked by the user\
ad_click_list_v003: [string,] - List of advertisement recommended applications clicked by the user\
ad_close_list_v001: [string,] - List of advertisement tasks closed by the user\
ad_close_list_v002: [string,] - List of advertiser IDs whose advertisements were closed by the user\
ad_close_list_v003: [string,] - List of advertisement recommended applications closed by the user\
pt_d: string - Timestamp\
log_id: int - Sample ID

## explanations for variables in feeds

u_userId: string - User ID\
u_phonePrice: string - Price of the user's device\
u_browserLifeCycle: string - User engagement on the browser\
u_browserMode: string - Browser service type\
u_feedLifeCycle: string - User engagement on news feeds\
u_refreshTimes: string - Average number of valid news feeds updates per day\
u_newsCatInterests: [string,] - Liked news feeds categories based on the user's click behavior\
u_newsCatDislike: [string,] - Disliked news feed categories\
u_newsCatInterestsST: [string,] - Short-term interests in news feed categories\
u_click_ca2_news: [string,] - Clicked news feed categories\
i_docId: string - Document ID of the news feed\
i_s_sourceId: string - Source ID of the news feed\
i_regionEntity: string - Regional entity ID of the news feed\
i_cat: string - Category ID of the news feed\
i_entities: [string,] - Entity IDs of the news feed\
i_dislikeTimes: string - Number of dislikes the news feeds received\
i_upTimes: string - Number of likes the news feed received\
i_dtype: string - Display type of the news feed\
e_ch: string - Channel\
e_m: string - Device model from which the event originated\
e_po: string - Position in the feed\
e_pl: string - Visit place\
e_rn: string - Refresh count\
e_section: string - News feed scene type\
e_et: string - Timestamp\
label: string - Click label (-1: No, 1: Yes)\
cilLabel: string - Like label (-1: No, 1: Yes)\
pro: string - news feed browsing progress

