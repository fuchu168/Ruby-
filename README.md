Ruby-
=====

 
def silly_nums(max)
    i=1;
     puts "result for silly_nums(max)"
    while i<max do
        if(((i%5==0) || (i%3==0)) && (i%15!=0)) 
            puts i;
        end
         i+=1;
    end
end

def silly_sum(numbers)
     sum=0;
     i=0;
   puts "result for  silly_sum(numbers)";
    numbers.each do |number|
        sum+=number*i;
        i+=1;
    end
    puts sum ;
end

def num_squares(max)
  k=Math.sqrt(max);
  res=k.to_i;
  puts "result for   num_squares(max)";
if(res==k)
     puts res-1;
  else
   puts res;
   end
end

    

    
n=[1,2,3];
 silly_sum(n);
num_squares(5) ;
silly_nums(20)
