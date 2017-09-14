# Orario
    My New Project, Making Simple Text Game With Complicated Simulation (In Orario)

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
            이름 = string
            성별 = string
            종족 = integer_id 
            이명 = { string* } 
            직업 = { integer_id* }
            소속 = { integer_id* }

            레벨 = integer

            힘 = integer
            내구 = integer
            기교 = integer
            민첩 = integer
            마력 = integer

            체력 = integer
            마법력 = integer
            공격력 = integer
            물리방어력 = integer
            마법방어력 = integer

            # functions..
            $체력 = { $assign = { /./체력 val = { $add = { 10 $multiple = { 10 /./내구 } } } } }
            $마법력 = { } 

            $공격력 = { }
            $물리방어력 = { }
            $마법방어력 = { }

            스킬 = {  integer_id* }
            마법 = {  integer_id* }

            인벤토리 = {  integer_id* }
            무기 = {  integer_id* }
            방어구 = {  integer_id* }
            악세서리 = {  integer_id* }

            상태 = {  integer_id* }
        }

