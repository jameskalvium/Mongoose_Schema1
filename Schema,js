const mongoose= require('mongoose');

const detailSchema= new mongoose.Schema({
    username:{
        type:String,
        required:true,
        unique:true,
    },
    email:{
        type:String,
        required:true,
        unique:true,
    },
    password:{
        type:String,
        required:true,
    },
    roles:{
        type:[String]
    },
    profileEle:{
        firstName:{
            type:String
        },
        lastName:{
            type:String
        },
        age:{
            type:Number
        }
    },
    login:{
        type:Date
    }
});

module.exports=mongoose.model('User',detailSchema);