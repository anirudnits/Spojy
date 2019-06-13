=================
Spojy
=================

Spojy provides programmers modules to conveniently gather various information about users as well as problems from the popular problem solving site SPOJ. The basic purpose of this package is the absence of a standard API from SPOJ and the lack of the open source projects on this issue.You might find this most useful for analzying and comparing user's SPOJ account and gain further insight on the areas that you or the user need to work on and improve. Typical usage
often looks like this::

	from spojy import profile_info
	from spojy import problem_info

	user_info = profile_info.get_profile("xyz")
	tags = problem_info.get_tags(["POWFIB", "ABCDEF"], proxy="localhost:3000")





