@startuml
start
:体力=0;
if(体力<=20) then (true)
:宿屋に泊まる;
else(false)
:頑張ってレベルを上げる;
endif
end
@enduml
