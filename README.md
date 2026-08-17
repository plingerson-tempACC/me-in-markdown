<h1>HI</h1>

<b>32</b>

I am Nathan Fenstad. I am looking forward to being in this class this year, since I have 7 years of experience with **Lua** (though progress has unfortunately slowed down lately because I have been using ChatGPT Plus to my advantage) and I like coding. I know a little bit of Python and JavaScript and HTML already.

This is something I created just now in Lua. I have made much more complicated scripts than this, but this is an example.
```lua
local op = {
    "good",
    "bad",
    "okay"
}

local function go(p)
    if p then
        print("lua is",op[math.random(1,#op)])

        for i = 0, 14 do
            local year = 2011+i
            print("I was",i,"years old in",year.."-"..year+1..".")
        end
        print("I am turning",2026-2011.."! I was born in ",year-i)
    else
        print("did not run")
    end
end
go(true)
```
When you run this code, it will print a random string from the table in front of "lua is". It will either say "lua is good", "lua is bad", or "lua is okay".
Then, it will print "I am _ years old in." from 0-14. The last number is my actual age!