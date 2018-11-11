# Top downde sign

是一种自上而下的编程方法。将项目分解，为一个一个小目的，再讲一个一个小目的再分解为更小的目的，直到这个目的容易实现为止。如此一来就可以将巨大的项目，分解成容易操作的块，将一次的思维量减少，从而减轻压力，也提高容错率。


注水

water_in_switch(open）

while water_volume <= a

    get_water_volume()

water_in_switch(close) 

浸泡

while time_counter1() <= b

洗衣

while time_counter2() <= c

    time_counter3() <= d

        motor_run(left）

    then
    
    time_counter4() <= d

        motor_run(right）

排水

while time_counter <= e

    water_out_switch(open)

while time_counter <= f

    motor_run(left)

motor_run(stop）

water_out_switch(close)

完成

halt(success) 