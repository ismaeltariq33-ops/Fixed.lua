local oldMax = math.max
math.max = function(...)
    local args = {...}
    if #args == 0 then
        return 0
    end
    for i = 1, #args do
        args[i] = tonumber(args[i]) or 0
    end
    return oldMax(table.unpack(args))
end

loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Blox-Fruit-Control-Update-78066"))()
