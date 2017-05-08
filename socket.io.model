// CMD Mapping - socket.io title event
/*
    CMD type:
        -Testing
        -Setting
        -Command
*/

var testing = {
    'head': head_number,
    'cmd': cmd_type
    /*  
        cmd :
            run_sq = "test all function",
            frame_up,
            frame_down,
            sweep_fw,
            sweep_bw,
            squeeze,
            rotate_fw,
            rotate_bw,
            heat

        example :
            {
                'head': 1,
                'cmd': 'frame_up'
            }
    */
}

var setting = {
    'name': setting_name, // setting name
    'round': round_number, // 20 pieces of shirt
    'head': [ // jsonarray head's setting 
        {
            'head': head_number, 
            'temperature': temp_val, // 0-20
            'heat_time': heat_time, // seconds
            'active': boolean, // open/close
            'speed_motor': speed_val, // 0-20 step 
            'speed_dir': ["bw" , "fw"] //speed direction. Type : enumeration -> backward or forward
        }
        //...
    ]
    /*
        exmaple:
            {
                'name': king rama IX
                'round': 50,
                'head':[
                     {
                        'head': 1, 
                        'temperature':20, // 0-20 step
                        'heat_time': 5, // 5s
                        'active': true, // open/close
                        'speed_motor': 15, // 0-20 step 
                        'speed_dir': "fw" //speed direction. Type : enumeration -> backward or forward
                    },
                    {
                        'head': 2, 
                        'temperature':20, // 0-20 step
                        'heat_time': 5, // 5s
                        'active': true, // open/close
                        'speed_motor': 15, // 0-20 step 
                        'speed_dir': "fw" //speed direction. Type : enumeration -> backward or forward
                    },
                    {
                        'head': 3, 
                        'temperature':20, // 0-20 step
                        'heat_time': 5, // 5s
                        'active': true, // open/close
                        'speed_motor': 15, // 0-20 step 
                        'speed_dir': "fw" //speed direction. Type : enumeration -> backward or forward
                    },
                    {
                        'head': 4, 
                        'temperature':20, // 0-20 step
                        'heat_time': 5, // 5s
                        'active': true, // open/close
                        'speed_motor': 15, // 0-20 step 
                        'speed_dir': "fw" //speed direction. Type : enumeration -> backward or forward
                    }
                ]
            }

    */
}


var cmd = {
    'cmd': command_type, //command type
    /*
        cmd:
            start,
            stop,
            pause,
            resume,
            skip

        example :
            {
                'cmd': start
            }

    */
}
