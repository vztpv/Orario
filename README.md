# Orario
    My New Project, Making Simple Text Game With Complicated Simulation (In Orario), Using ClauText?

# ToDo
    1. Making Characters.
      - Status, Level, Skills, Magics, ...
    2. Making Monsters.
    3. Making Tower.
    4. Making Guild.
    5. Making City ( Orario ).
    6. Making Gods.
    7. Making Events. (Random, Story?)
    8. Making Economy?.
    9. Making Party?.

# Goal
     1. Opened Code?
     2. Easy? Modding.
    
# Code Example?
    integer_id = {
        이름 = { type = string option = make_from_file from = { "이름.txt" } }
        성별 = { type = string option = make from = { "남자" "여자" } }
        종족 = { type = integer_id }
        이명 = { type = string* } 
        직업 = { type = integer_id* }
        소속 = { type = integer_id* }

        레벨 = { type = integer } 

        힘 = { type = integer }
        내구 = { type = integer }
        기교 = { type = integer }
        민첩 = { type = integer }
        마력 = { type = integer }

        체력 = { type = integer }
        체력Max = { type = integer }
        마법력 = { type = integer }
        마법력Max = { type = integer }
        공격력 = { type = integer }
        물리방어력 = { type = integer }
        마법방어력 = { type = integer }

        # functions..
        $체력Max = { $assign = { /./체력Max val = { $add = { 10 $multiple = { 10 /./내구 } } } } }
        $마법력Max = { } 

        $공격력 = { }
        $물리방어력 = { }
        $마법방어력 = { }

        스킬 = {  type = integer_id* }
        마법 = {  type = integer_id* }

        인벤토리 = {  type = integer_id* }
        무기 = {  type = integer_id* }
        방어구 = {  type = integer_id* }
        악세서리 = {  type = integer_id* }

        상태 = {  type = integer_id* }
    }


