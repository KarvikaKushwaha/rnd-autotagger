rnd-autotagger

link for the demo vedio :https://www.loom.com/share/9a20fc31225849d7b6c9067259ae7f04

'Index_management.py' will manage the the index for the autotagger.

'Index_management.py' can be run by command 'python Index_management.py'

It has information of data like md5hash,bestsellerranks,classifcation,mltags,familyid for index structure reference you can look at 'indexResult.json'.


Missing_styles.py will get the all the styles of a family for which CPs have marked 'Yes'. 

Input for missing_Styles.py will a input.csv which will have information at the head 'md5,cp_tag'.

Missing_styles.py can be run by 'python missing_styles.py tag_name'.

