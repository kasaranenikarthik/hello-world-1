# hello-world
my first repository in github created by me on august 10 2018
My nane is Tharun. Now I am going to make my first commit.
select distinct course_id
from section
where semester = ’Fall’ and year= 2009 and 
           course_id  not in (select course_id
                                 from section
                                 where semester = ’Spring’ and year= 2010);
