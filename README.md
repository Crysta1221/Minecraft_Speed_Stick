# Minecraft Speed Stick
マインクラフトで足が速くなる棒を入手できるリポジトリ。

# How to Use
> WARN:  
> このコマンドは、Minecraft Java Edition 1.16.5でのみ動作確認しています。ただしマルチ対応かの動作は未確認です。  
> また統合版では使用できません。

① Minecraft Java Edition 1.16.5でワールドを生成してください。<br>
  ●生成時にチートの許可をオンにしてください。出ないとできません。<br>
② チャット欄で次のコマンドを入れます。　`/give @p command_block` <br>
③ コマンドブロックを入手した後設置し、 [Commands](https://github.com/Crysta1221/Minecraft_Speed_Stick#commands) にあるコマンドをコピーしてください。

# Commands
- 足が150%速くなる棒  
```
/give @p stick{display:{Name:'{"text":"足が+150%速くなる棒","color":"dark_purple"}'},Enchantments:[{}],AttributeModifiers:[{AttributeName:"generic.movement_speed",Name:"generic.movement_speed",Amount:1.5,Operation:1,UUID:[I;-1390069524,1055409027,-1343835045,-1630410346],Slot:"mainhand"}]} 1
```
- 足が50%速くなる棒
```
/give @p stick{display:{Name:'{"text":"足が+50%速くなる棒","color":"dark_purple"}'},Enchantments:[{}],AttributeModifiers:[{AttributeName:"generic.movement_speed",Name:"generic.movement_speed",Amount:0.5,Operation:1,UUID:[I;-1390069524,1055409027,-1343835045,-1630410346],Slot:"mainhand"}]} 1
```

# Change Command
速度をもう少し速くしたい、遅くしたい場合は、 `stick` のNBTデータである `AttributeModifiers` の項目を探し、その中にある `Amount:` を探してください。  
`Amount:1.5` の場合、150%の速度上昇になります。 名前を変える場合は、`stick` NBTデータ内の `display` の項目にある `Name:` 内のJsonをお好きに変えてください。

# Quote  
このコマンドを利用するにあたり、利用申請は不要です。お好きにお使いください。
