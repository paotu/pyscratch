# pyscratch API使用手册

---
## 运动  ##




---

#### move(steps)  
移动指定距离  
参数  
steps 


#### turn_right(degrees)   
右转指定角度  
参数：
degrees 度  

 
#### turn_left(degrees)     
左转指定角度  
参数：
degrees 度  


#### go_to_random_position()  
移动到随机位置  


#### go_to_mouse_pointer()  
移动到鼠标位置  


#### go_to(x,y)  
移动到坐标
参数  
x x坐标  
y y坐标  


#### glide_to_random_position(secs)
在指定时间内，滑动到随机位置
参数：
secs 时间，单位秒


#### glide_to_mouse_pointer(secs)  
在指定时间内，滑动到鼠标位置  
参数：
secs 时间，单位秒  


#### glide_to(secs,x,y)  
在指定时间内，滑动到坐标位置  
参数： 
secs 时间，单位秒  
x x坐标  
y y坐标  


#### point(direction)  
朝向某个方向  
参数：  
direction 单位度  


#### point_towards_mouse_pointer()

#### change_x_by(x)

#### set_x_to(x)

#### change_y_by(y)

#### set_y_to(y)

#### bounce_if_on_edge()

#### set_rotation_style(style)

#### x

#### y

#### direction  





---


## 外观

#### say_for_seconds

#### say

#### think_for_seconds

#### think_for_seconds

#### switch_costume_to

造型切换为


#### next_costume

#### switch_backdrop_to

#### next_backdrop

#### change_size_by

#### set_size_to

#### change_effect_by()

effect 枚举

#### set_effect_to()

effect 枚举

#### clear_graphic_effects()

#### show()

#### hide()

#### goto_front_layer()

#### goto_back_layer()

#### go_forward_layer(num)

#### go_backward_layer(num)

#### costume{}
字典类型变量，可以通过[数组] 或 [名称] 访问


#### backdrop{}
字典类型变量，可以通过[数组] 或 [名称] 访问


#### size

## 声音

#### play_sound_until_done(sound)


#### play_sound(sound)


#### stop_all_sounds()


#### change_effect_by()
(和外观都有类似方法)

#### set_effect_to()

参数：
声调 pitch
左右平衡 pan_left_right


#### clear_sound_effects()
清除所有音效

#### change_volumn_by()
将音量增加

#### set_volumn_to()
将音量设为 %

#### volumn



## 事件

#### when_start()


#### when_key_pressd()


#### when_clicked()


#### when_backdrop_switch_to()


#### when_loudness_greater_than()


#### when_timer_greater_than()


#### when_receive()


#### broadcast(message)


#### broadcast_and_wait(message)



## 控制


#### wait(seconds)


#### wait_util(message)


#### stop_all()


#### stop_this()


#### stop_other()


#### when_start_as_clone()


#### clone(sprite)


#### delete_this_clone()



## 侦测

#### touching_mouse_pointer()


#### touching_edge()


#### touching_color(color)


#### touching_color(color1,color2)


#### distance_to_mouse_pointer()


#### ask_and_wait(question)


#### key_pressed(key)


#### mouse_down()  


#### mouse_x  


#### mouse_y  


#### set_drag_mode(mode)
参数：
mode True 或 False  


#### loudness


#### timer


#### reset_timer()  


#### backdrop


#### backdrop_name


#### volume


#### year


#### month


#### date


#### day_of_week


#### hour


#### minute


#### second
