# RHEY-STORE
JUAL BELI AKUN
const chalk = require("chalk")
const fs = require("fs")

global.ownerNumber = ["62838984457888@s.whatsapp.net"]
global.nomerOwner = "62838984457888"
global.nomorOwner = ['62838984457888']
global.namaDeveloper = "RheyBotz"
global.nameGEDE = "RHEYBOTZ"
global.namaBot = "RheyBotz WhatsApp"
global.packname = ""
global.wame = "https://wa.me/setting"
global.author = "Sticker By RheyBotz"
global.ovo = "0877-0504-8235" // isi nomor ovo lu
global.dana = "GAK ADA KE BLOCK" // 085791925313
global.gopay = "0877-0504-8235" // isi nomor gopay lu
global.shopeepay = "0877-0504-8235" // isi nomor shopeepay lu
global.pulsa = "0857-9814-5596" // isi nomor kartu lu
global.thumb = fs.readFileSync("./thumb.png")
global.thumbqris = fs.readFileSync("./qris.jpg")

let file = require.resolve(__filename) 
fs.watchFile(file, () => {
fs.unwatchFile(file)
console.log(chalk.redBright(`Update ${__filename}`))
delete require.cache[file]
require(file)
})

/*

Thanks To By RheyBotz
Base Ori By RheyBotz
Ubah Nomor Owner?
Ganti Di File ./owner.json
Harap Jangan Jual Sc Ini
Karena Sc Ini Free Langsung Dari
Youtube : https://youtube.com/@kangbotwhatsapp

*/
