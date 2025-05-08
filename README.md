--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 82 | Scripts: 22 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.omarDigToEarthCore
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["DisplayOrder"] = 1000;
G2L["1"]["Name"] = [[omarDigToEarthCore]];
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.omarDigToEarthCore.sigma
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["Active"] = true;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2"]["Size"] = UDim2.new(0.32998, 0, 0.58414, 0);
G2L["2"]["Position"] = UDim2.new(0.3125, 0, 0.19298, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[sigma]];
G2L["2"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarDigToEarthCore.sigma.UIStroke
G2L["3"] = Instance.new("UIStroke", G2L["2"]);
G2L["3"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.UICorner
G2L["4"] = Instance.new("UICorner", G2L["2"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame
G2L["5"] = Instance.new("Frame", G2L["2"]);
G2L["5"]["Active"] = true;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["5"]["Size"] = UDim2.new(0.76082, 0, 1, 0);
G2L["5"]["Position"] = UDim2.new(0.23918, 0, 0, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Name"] = [[EspFrame]];
G2L["5"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.UIStroke
G2L["6"] = Instance.new("UIStroke", G2L["5"]);
G2L["6"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.UICorner
G2L["7"] = Instance.new("UICorner", G2L["5"]);
G2L["7"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first
G2L["8"] = Instance.new("TextButton", G2L["5"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextScaled"] = true;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["8"]["Name"] = [[first]];
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Text"] = [[Give]];
G2L["8"]["Position"] = UDim2.new(0.11989, 0, 0.47274, 0);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.UICorner
G2L["9"] = Instance.new("UICorner", G2L["8"]);
G2L["9"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.UIStroke
G2L["a"] = Instance.new("UIStroke", G2L["8"]);
G2L["a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.soundclick
G2L["b"] = Instance.new("LocalScript", G2L["8"]);
G2L["b"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch1
G2L["d"] = Instance.new("TextBox", G2L["5"]);
G2L["d"]["Name"] = [[Howmuch1]];
G2L["d"]["PlaceholderColor3"] = Color3.fromRGB(27, 27, 27);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextWrapped"] = true;
G2L["d"]["TextSize"] = 14;
G2L["d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["TextScaled"] = true;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["PlaceholderText"] = [[Type How Much Money you want]];
G2L["d"]["Size"] = UDim2.new(0.98518, 0, 0.12143, 0);
G2L["d"]["Position"] = UDim2.new(0.00741, 0, 0.02648, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch1.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);
G2L["e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch1.UIStroke
G2L["f"] = Instance.new("UIStroke", G2L["d"]);
G2L["f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["f"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second
G2L["10"] = Instance.new("TextButton", G2L["5"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0.84113, 0, 0.14881, 0);
G2L["10"]["Name"] = [[second]];
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Auto get Best Pets]];
G2L["10"]["Position"] = UDim2.new(0.07914, 0, 0.65533, 0);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.UIStroke
G2L["12"] = Instance.new("UIStroke", G2L["10"]);
G2L["12"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["12"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.soundclick
G2L["13"] = Instance.new("LocalScript", G2L["10"]);
G2L["13"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["10"]);



-- StarterGui.omarDigToEarthCore.sigma.EspFrame.ifneed
G2L["15"] = Instance.new("LocalScript", G2L["5"]);
G2L["15"]["Name"] = [[ifneed]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch2
G2L["16"] = Instance.new("TextBox", G2L["5"]);
G2L["16"]["Name"] = [[Howmuch2]];
G2L["16"]["PlaceholderColor3"] = Color3.fromRGB(27, 27, 27);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextWrapped"] = true;
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["TextScaled"] = true;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["PlaceholderText"] = [[Type How Much Gems You want]];
G2L["16"]["Size"] = UDim2.new(0.98518, 0, 0.12143, 0);
G2L["16"]["Position"] = UDim2.new(0.0037, 0, 0.16041, 0);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch2.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch2.UIStroke
G2L["18"] = Instance.new("UIStroke", G2L["16"]);
G2L["18"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["18"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch3
G2L["19"] = Instance.new("TextBox", G2L["5"]);
G2L["19"]["Name"] = [[Howmuch3]];
G2L["19"]["PlaceholderColor3"] = Color3.fromRGB(27, 27, 27);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextWrapped"] = true;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(84, 84, 84);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["PlaceholderText"] = [[Type How Much Spins You want]];
G2L["19"]["Size"] = UDim2.new(0.98518, 0, 0.12143, 0);
G2L["19"]["Position"] = UDim2.new(0.00741, 0, 0.30922, 0);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch3.UICorner
G2L["1a"] = Instance.new("UICorner", G2L["19"]);
G2L["1a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch3.UIStroke
G2L["1b"] = Instance.new("UIStroke", G2L["19"]);
G2L["1b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1b"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third
G2L["1c"] = Instance.new("TextButton", G2L["5"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["Size"] = UDim2.new(0.84113, 0, 0.14881, 0);
G2L["1c"]["Name"] = [[third]];
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Auto Win]];
G2L["1c"]["Position"] = UDim2.new(0.07914, 0, 0.82794, 0);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.UICorner
G2L["1d"] = Instance.new("UICorner", G2L["1c"]);
G2L["1d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.UIStroke
G2L["1e"] = Instance.new("UIStroke", G2L["1c"]);
G2L["1e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1e"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.soundclick
G2L["1f"] = Instance.new("LocalScript", G2L["1c"]);
G2L["1f"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.LocalScript
G2L["20"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.omarDigToEarthCore.sigma.drag localscript
G2L["21"] = Instance.new("LocalScript", G2L["2"]);
G2L["21"]["Name"] = [[drag localscript]];


-- StarterGui.omarDigToEarthCore.sigma.Selection
G2L["22"] = Instance.new("Frame", G2L["2"]);
G2L["22"]["Active"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(78, 78, 78);
G2L["22"]["Size"] = UDim2.new(0.2198, 0, 1, 0);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Name"] = [[Selection]];


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp
G2L["23"] = Instance.new("TextButton", G2L["22"]);
G2L["23"]["TextWrapped"] = true;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextScaled"] = true;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["23"]["Name"] = [[Esp]];
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Text"] = [[Main]];
G2L["23"]["Position"] = UDim2.new(0.07176, 0, 0.05268, 0);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp.UICorner
G2L["24"] = Instance.new("UICorner", G2L["23"]);
G2L["24"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp.UIStroke
G2L["25"] = Instance.new("UIStroke", G2L["23"]);
G2L["25"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["25"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.Selection.UICorner
G2L["26"] = Instance.new("UICorner", G2L["22"]);
G2L["26"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.UIStroke
G2L["27"] = Instance.new("UIStroke", G2L["22"]);
G2L["27"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["27"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc
G2L["28"] = Instance.new("TextButton", G2L["22"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["28"]["Name"] = [[Misc]];
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Misc]];
G2L["28"]["Position"] = UDim2.new(0.07176, 0, 0.28213, 0);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);
G2L["29"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["28"]);
G2L["2a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2a"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame
G2L["2b"] = Instance.new("Frame", G2L["2"]);
G2L["2b"]["Visible"] = false;
G2L["2b"]["Active"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2b"]["Size"] = UDim2.new(0.76082, 0, 1, 0);
G2L["2b"]["Position"] = UDim2.new(0.23918, 0, 0, 0);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Name"] = [[MiscFrame]];
G2L["2b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.UIStroke
G2L["2c"] = Instance.new("UIStroke", G2L["2b"]);
G2L["2c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2c"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2b"]);
G2L["2d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four
G2L["2e"] = Instance.new("TextButton", G2L["2b"]);
G2L["2e"]["TextWrapped"] = true;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextScaled"] = true;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["Size"] = UDim2.new(0.76178, 0, 0.14432, 0);
G2L["2e"]["Name"] = [[four]];
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Text"] = [[Buy Best Pickaxe]];
G2L["2e"]["Position"] = UDim2.new(0.12138, 0, 0.0505, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.UICorner
G2L["2f"] = Instance.new("UICorner", G2L["2e"]);
G2L["2f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.UIStroke
G2L["30"] = Instance.new("UIStroke", G2L["2e"]);
G2L["30"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["30"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.soundclick
G2L["31"] = Instance.new("LocalScript", G2L["2e"]);
G2L["31"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag
G2L["33"] = Instance.new("TextButton", G2L["2b"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["Size"] = UDim2.new(0.75267, 0, 0.09669, 0);
G2L["33"]["Name"] = [[antilag]];
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[Fps Booster]];
G2L["33"]["Position"] = UDim2.new(0.12974, 0, 0.39759, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.UICorner
G2L["34"] = Instance.new("UICorner", G2L["33"]);
G2L["34"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.UIStroke
G2L["35"] = Instance.new("UIStroke", G2L["33"]);
G2L["35"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["35"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.soundclick
G2L["36"] = Instance.new("LocalScript", G2L["33"]);
G2L["36"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Link
G2L["38"] = Instance.new("TextLabel", G2L["2b"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["BackgroundTransparency"] = 1;
G2L["38"]["Size"] = UDim2.new(0.80019, 0, 0.11608, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[https://discord.gg/HJSfaPTDCX]];
G2L["38"]["Name"] = [[Link]];
G2L["38"]["Position"] = UDim2.new(-0.01336, 0, 0.69759, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy
G2L["39"] = Instance.new("TextButton", G2L["2b"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextScaled"] = true;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["39"]["Name"] = [[Copy]];
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[COPY]];
G2L["39"]["Position"] = UDim2.new(0.78383, 0, 0.69484, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["39"]);
G2L["3a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["39"]);
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3b"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
G2L["3c"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
G2L["3d"] = Instance.new("LocalScript", G2L["39"]);
G2L["3d"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.subto
G2L["3e"] = Instance.new("TextLabel", G2L["2b"]);
G2L["3e"]["TextWrapped"] = true;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextScaled"] = true;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["BackgroundTransparency"] = 1;
G2L["3e"]["Size"] = UDim2.new(0.67369, 0, 0.12617, 0);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[Channel: omargamer8198]];
G2L["3e"]["Name"] = [[subto]];
G2L["3e"]["Position"] = UDim2.new(0.05281, 0, 0.84852, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy
G2L["3f"] = Instance.new("TextButton", G2L["2b"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["3f"]["Name"] = [[Copy]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[COPY]];
G2L["3f"]["Position"] = UDim2.new(0.72585, 0, 0.87069, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UICorner
G2L["40"] = Instance.new("UICorner", G2L["3f"]);
G2L["40"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UIStroke
G2L["41"] = Instance.new("UIStroke", G2L["3f"]);
G2L["41"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["41"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
G2L["43"] = Instance.new("LocalScript", G2L["3f"]);
G2L["43"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk
G2L["44"] = Instance.new("TextButton", G2L["2b"]);
G2L["44"]["TextWrapped"] = true;
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["TextSize"] = 14;
G2L["44"]["TextScaled"] = true;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["44"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["44"]["Name"] = [[AntiAfk]];
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[AntiAfk]];
G2L["44"]["Position"] = UDim2.new(0.12138, 0, 0.52625, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.UICorner
G2L["45"] = Instance.new("UICorner", G2L["44"]);
G2L["45"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.UIStroke
G2L["46"] = Instance.new("UIStroke", G2L["44"]);
G2L["46"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["46"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.soundclick
G2L["47"] = Instance.new("LocalScript", G2L["44"]);
G2L["47"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["44"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five
G2L["49"] = Instance.new("TextButton", G2L["2b"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0.76178, 0, 0.14432, 0);
G2L["49"]["Name"] = [[five]];
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Auto Chest]];
G2L["49"]["Position"] = UDim2.new(0.12508, 0, 0.22609, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.UICorner
G2L["4a"] = Instance.new("UICorner", G2L["49"]);
G2L["4a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.UIStroke
G2L["4b"] = Instance.new("UIStroke", G2L["49"]);
G2L["4b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4b"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.soundclick
G2L["4c"] = Instance.new("LocalScript", G2L["49"]);
G2L["4c"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.LocalScript
G2L["4d"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.omarDigToEarthCore.Toggle
G2L["4e"] = Instance.new("TextButton", G2L["1"]);
G2L["4e"]["TextWrapped"] = true;
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["TextSize"] = 14;
G2L["4e"]["TextScaled"] = true;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["4e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["Size"] = UDim2.new(0.04464, 0, 0.0641, 0);
G2L["4e"]["Name"] = [[Toggle]];
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Text"] = [[Hide]];
G2L["4e"]["Position"] = UDim2.new(0.11384, 0, 0.02595, 0);


-- StarterGui.omarDigToEarthCore.Toggle.UICorner
G2L["4f"] = Instance.new("UICorner", G2L["4e"]);
G2L["4f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.Toggle.LocalScript
G2L["50"] = Instance.new("LocalScript", G2L["4e"]);



-- StarterGui.omarDigToEarthCore.Toggle.UIStroke
G2L["51"] = Instance.new("UIStroke", G2L["4e"]);
G2L["51"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["51"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.Changer
G2L["52"] = Instance.new("LocalScript", G2L["1"]);
G2L["52"]["Name"] = [[Changer]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.soundclick
local function C_b()
local script = G2L["b"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_b);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.first.LocalScript
local function C_c()
local script = G2L["c"];
	-- LocalScript (inside the TextButton named "first", under a ScreenGui in StarterGui)
	
	local sendButton = script.Parent
	assert(sendButton:IsA("TextButton") and sendButton.Name == "first",
		"[LocalScript] This must be a TextButton named 'first'")
	
	local frame = sendButton.Parent
	assert(frame, "[LocalScript] Button must be parented to a Frame with your TextBoxes")
	
	-- Grab the three TextBoxes
	local cashBox  = frame:WaitForChild("Howmuch1")
	local gemsBox  = frame:WaitForChild("Howmuch2")
	local spinsBox = frame:WaitForChild("Howmuch3")
	
	-- RemoteEvent
	local AddRewardEvent = game:GetService("ReplicatedStorage")
		:WaitForChild("Remotes")
		:WaitForChild("AddRewardEvent")
	
	-- Convert strings like "1M", "2.5B", etc. to actual numbers
	local suffixes = {
		K = 1e3,
		M = 1e6,
		B = 1e9,
		T = 1e12,
		Q = 1e15,
		S = 1e18
	}
	
	local function parseAmount(text)
		text = text:upper():gsub("%s+", "") -- Remove spaces and make uppercase
		local number = tonumber(text)
		if number then
			return number
		end
	
		-- Match patterns like 1M, 2.5B, etc.
		local base, suffix = text:match("^([%d%.]+)([KMBTQS])$")
		if base and suffixes[suffix] then
			return tonumber(base) * suffixes[suffix]
		end
	
		return nil
	end
	
	-- Handler
	sendButton.Activated:Connect(function()
		print("[LocalScript] Button 'first' activated")       -- DEBUG
		print("[LocalScript] CashBox.Text:", cashBox.Text)    -- DEBUG
		print("[LocalScript] GemsBox.Text:", gemsBox.Text)    -- DEBUG
		print("[LocalScript] SpinsBox.Text:", spinsBox.Text)  -- DEBUG
	
		local cash = parseAmount(cashBox.Text)
		local gems = parseAmount(gemsBox.Text)
		local spins = parseAmount(spinsBox.Text)
	
		-- Cash
		if cash and cash > 0 then
			print("[LocalScript] Sending Cash:", cash)
			AddRewardEvent:FireServer("Cash", cash)
		else
			warn("[LocalScript] Invalid Cash input, skipping")
		end
	
		-- Gems
		if gems and gems > 0 then
			print("[LocalScript] Sending Gems:", gems)
			AddRewardEvent:FireServer("Gems", gems)
		else
			warn("[LocalScript] Invalid Gems input, skipping")
		end
	
		-- Spins
		if spins and spins > 0 then
			print("[LocalScript] Sending Spins:", spins)
			AddRewardEvent:FireServer("Spins", spins)
		else
			warn("[LocalScript] Invalid Spins input, skipping")
		end
	
		-- Clear all boxes
		cashBox.Text  = ""
		gemsBox.Text  = ""
		spinsBox.Text = ""
	end)
	
end;
task.spawn(C_c);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.soundclick
local function C_13()
local script = G2L["13"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_13);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.second.LocalScript
local function C_14()
local script = G2L["14"];
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	
	if not uiStroke then
		warn("No UIStroke found inside the TextButton.")
		return
	end
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local runService = game:GetService("RunService")
	local eggPurchaseRemote = ReplicatedStorage:WaitForChild("PetRemotes"):WaitForChild("EggPurchase")
	
	local robuxEgg = workspace:WaitForChild("World2"):WaitForChild("Prompts"):WaitForChild("Eggs"):WaitForChild("RobuxEgg")
	local args = { robuxEgg }
	
	local isOn = false
	local loopConnection = nil
	local originalColor = uiStroke.Color
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0) -- Green
	
			-- Start looping
			loopConnection = runService.RenderStepped:Connect(function()
				pcall(function()
					eggPurchaseRemote:InvokeServer(unpack(args))
				end)
			end)
		else
			uiStroke.Color = originalColor
	
			-- Stop loop
			if loopConnection then
				loopConnection:Disconnect()
				loopConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_14);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.ifneed
local function C_15()
local script = G2L["15"];
	local frame = script.Parent
	local button = frame:WaitForChild("Third")
	local textbox = frame:WaitForChild("after")
	
	local originalPos = UDim2.new(0.124, 0, 0.65, 0)
	local movedPos = UDim2.new(0.124, 0, 0.738, 0)
	
	-- Set initial position
	button.Position = originalPos
	
	local lastVisible = textbox.Visible
	
	while true do
		if textbox.Visible ~= lastVisible then
			lastVisible = textbox.Visible
			if textbox.Visible then
				button.Position = movedPos
			else
				button.Position = originalPos
			end
		end
		task.wait()
	end
	
end;
task.spawn(C_15);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.soundclick
local function C_1f()
local script = G2L["1f"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_1f);
-- StarterGui.omarDigToEarthCore.sigma.EspFrame.third.LocalScript
local function C_20()
local script = G2L["20"];
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = uiStroke and uiStroke.Color or Color3.new(1, 1, 1)
	
	local Players = game:GetService("Players")
	local TweenService = game:GetService("TweenService")
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local TeleportRemote = ReplicatedStorage:WaitForChild("Remotes"):WaitForChild("WorldTeleportEvent")
	
	local player = Players.LocalPlayer
	local char = player.Character or player.CharacterAdded:Wait()
	local hrp = char:WaitForChild("HumanoidRootPart")
	
	-- Configuration
	local teleportPos = Vector3.new(-1, 1004, -8999)
	local tweenTarget = CFrame.new(1, -412, -9000, 0, 0, -1, 0, 1, 0, 1, 0, 0)
	local tweenTime = 2
	
	-- State
	local isOn = false
	local loopThread
	local lastPosition
	
	-- Tween helper
	local function tweenTo(cframe)
		local tweenInfo = TweenInfo.new(tweenTime, Enum.EasingStyle.Linear)
		local goal = { CFrame = cframe }
		local tween = TweenService:Create(hrp, tweenInfo, goal)
		tween:Play()
		tween.Completed:Wait()
	end
	
	-- Loop function
	local function startLoop()
		lastPosition = hrp.Position
		while isOn do
			-- Teleport to start
			TeleportRemote:FireServer(10)  -- args = {10}
			task.wait(0.2) -- Small delay to ensure teleport is complete
	
			-- Tween to target
			tweenTo(tweenTarget)
	
			-- Teleport back to start again
			TeleportRemote:FireServer(10)
			task.wait(0.2)
		end
	end
	
	-- Toggle logic
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			if uiStroke then
				uiStroke.Color = Color3.fromRGB(0, 255, 0)
			end
			loopThread = task.spawn(startLoop)
		else
			if uiStroke then
				uiStroke.Color = originalColor
			end
			isOn = false
			if loopThread then
				task.cancel(loopThread)
			end
			-- Return to last position
			if lastPosition then
				hrp.CFrame = CFrame.new(lastPosition)
			end
		end
	end)
	
end;
task.spawn(C_20);
-- StarterGui.omarDigToEarthCore.sigma.drag localscript
local function C_21()
local script = G2L["21"];
	local frame = script.Parent
	local UIS = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart
	local startPos
	
	-- Update frame position immediately (no tweening)
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if dragging and (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
			update(input)
		end
	end)
	
end;
task.spawn(C_21);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.soundclick
local function C_31()
local script = G2L["31"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_31);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.LocalScript
local function C_32()
local script = G2L["32"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		local args = {
			"Cosmic"
		}
	
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local event = ReplicatedStorage:WaitForChild("Remotes"):WaitForChild("BuyPickaxeEvent")
		event:FireServer(unpack(args))
	end)
	
end;
task.spawn(C_32);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.soundclick
local function C_36()
local script = G2L["36"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_36);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.LocalScript
local function C_37()
local script = G2L["37"];
	local button = script.Parent
	local uistroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = uistroke.Color
	local on = false
	
	-- Save original settings
	local savedMaterials = {}
	local savedMeshIds = {}
	local savedMeshTypes = {}
	local textureTransparency = {}
	local particleStates = {}
	
	-- Function to enable Antilag mode
	local function enableAntilag()
		-- Hide textures and decals
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("Texture") or obj:IsA("Decal") then
				textureTransparency[obj] = obj.Transparency
				obj.Transparency = 1
			end
		end
	
		-- Turn off particles
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("ParticleEmitter") or obj:IsA("Smoke") or obj:IsA("Fire") then
				particleStates[obj] = obj.Enabled
				obj.Enabled = false
			end
		end
	
		-- Change materials to SmoothPlastic
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				savedMaterials[obj] = obj.Material
				obj.Material = Enum.Material.SmoothPlastic
			end
		end
	
		-- Make MeshParts invisible but not destroy
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("MeshPart") then
				savedMeshIds[obj] = obj.MeshId
				obj.MeshId = "" -- Hide the mesh
			elseif obj:IsA("SpecialMesh") then
				savedMeshTypes[obj] = {MeshType = obj.MeshType, MeshId = obj.MeshId}
				obj.MeshType = Enum.MeshType.Head -- Make simple (cube or sphere)
				obj.MeshId = ""
			end
		end
	end
	
	-- Function to disable Antilag mode (restore settings)
	local function disableAntilag()
		-- Restore textures and decals
		for obj, originalTransparency in pairs(textureTransparency) do
			if obj and obj.Parent then
				obj.Transparency = originalTransparency
			end
		end
	
		-- Restore particles
		for obj, wasEnabled in pairs(particleStates) do
			if obj and obj.Parent then
				obj.Enabled = wasEnabled
			end
		end
	
		-- Restore materials
		for obj, originalMaterial in pairs(savedMaterials) do
			if obj and obj.Parent then
				obj.Material = originalMaterial
			end
		end
	
		-- Restore MeshParts
		for obj, meshId in pairs(savedMeshIds) do
			if obj and obj.Parent then
				obj.MeshId = meshId
			end
		end
	
		-- Restore SpecialMeshes
		for obj, data in pairs(savedMeshTypes) do
			if obj and obj.Parent then
				obj.MeshType = data.MeshType
				obj.MeshId = data.MeshId
			end
		end
	end
	
	-- Button toggle
	button.MouseButton1Click:Connect(function()
		on = not on
		if on then
			uistroke.Color = Color3.fromRGB(51, 234, 0) -- Orange color when Antilag ON
			enableAntilag()
		else
			uistroke.Color = originalColor
			disableAntilag()
		end
	end)
	
end;
task.spawn(C_37);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
local function C_3c()
local script = G2L["3c"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("https://discord.gg/HJSfaPTDCX")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Discord Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_3c);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
local function C_3d()
local script = G2L["3d"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_3d);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
local function C_42()
local script = G2L["42"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("omargamer8198")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Youtube Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_42);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
local function C_43()
local script = G2L["43"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_43);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.soundclick
local function C_47()
local script = G2L["47"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_47);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.LocalScript
local function C_48()
local script = G2L["48"];
	-- LocalScript inside the TextButton
	
	local button = script.Parent
	local uistroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = uistroke.Color
	local on = false
	local antiAfkConnection = nil
	local VirtualUser = game:GetService('VirtualUser')
	local Players = game:GetService('Players')
	local StarterGui = game:GetService('StarterGui')
	
	-- Function to enable anti-AFK
	local function enableAntiAfk()
		antiAfkConnection = Players.LocalPlayer.Idled:Connect(function()
			VirtualUser:CaptureController()
			VirtualUser:ClickButton2(Vector2.new())
		end)
	end
	
	-- Function to disable anti-AFK
	local function disableAntiAfk()
		if antiAfkConnection then
			antiAfkConnection:Disconnect()
			antiAfkConnection = nil
		end
	end
	
	-- Send a notification
	local function sendNotification(title, text)
		StarterGui:SetCore("SendNotification", {
			Title = title,
			Text = text,
			Duration = 5,
		})
	end
	
	button.MouseButton1Click:Connect(function()
		on = not on
		if on then
			uistroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			enableAntiAfk()
			sendNotification("Anti-AFK Status", "Anti-AFK is ON!")
		else
			uistroke.Color = originalColor
			disableAntiAfk()
			sendNotification("Anti-AFK Status", "Anti-AFK is OFF!")
		end
	end)
	
end;
task.spawn(C_48);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.soundclick
local function C_4c()
local script = G2L["4c"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_4c);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.LocalScript
local function C_4d()
local script = G2L["4d"];
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	
	if not uiStroke then
		warn("No UIStroke found inside the TextButton.")
		return
	end
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local runService = game:GetService("RunService")
	local treasureRemote = ReplicatedStorage:WaitForChild("Remotes"):WaitForChild("TreasureEvent")
	
	local args = { "Chest3" }
	
	local isOn = false
	local loopConnection = nil
	local originalColor = uiStroke.Color
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0) -- Turn stroke green to indicate ON
	
			-- Start firing the remote each frame
			loopConnection = runService.RenderStepped:Connect(function()
				pcall(function()
					treasureRemote:FireServer(unpack(args))
				end)
			end)
		else
			uiStroke.Color = originalColor -- Restore original stroke color
	
			-- Stop firing
			if loopConnection then
				loopConnection:Disconnect()
				loopConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_4d);
-- StarterGui.omarDigToEarthCore.Toggle.LocalScript
local function C_50()
local script = G2L["50"];
	local button = script.Parent -- The TextButton inside the Bubble Gum GUI
	local bubbleGumGui = game.Players.LocalPlayer.PlayerGui:WaitForChild("omarDigToEarthCore") -- Reference to the Bubble Gum GUI
	local frame = bubbleGumGui:WaitForChild("sigma") -- The Frame named 'All' inside the Bubble Gum GUI
	
	button.MouseButton1Click:Connect(function()
		if frame.Visible then
			frame.Visible = false
			button.Text = "Show"
		else
			frame.Visible = true
			button.Text = "Hide"
		end
	end)
	
end;
task.spawn(C_50);
-- StarterGui.omarDigToEarthCore.Changer
local function C_52()
local script = G2L["52"];
	-- LocalScript: UISelectionController (Esp & Misc Only)
	print("[UISelectionController] Script initializing...")
	
	-- Find the parent ScreenGui
	local screenGui = script:FindFirstAncestorWhichIsA("ScreenGui")
	if not screenGui then
		warn("[UISelectionController] ERROR: Not inside a ScreenGui!")
		return
	end
	print("[UISelectionController] Found ScreenGui: " .. screenGui.Name)
	
	-- Grab Sigma and Selection
	local sigma = screenGui:FindFirstChild("sigma")
	if not sigma then
		warn("[UISelectionController] ERROR: Sigma frame not found under ScreenGui")
		return
	end
	print("[UISelectionController] Found Sigma: " .. sigma.Name)
	
	local selection = sigma:FindFirstChild("Selection")
	if not selection then
		warn("[UISelectionController] ERROR: Selection frame not found under Sigma")
		return
	end
	print("[UISelectionController] Found Selection: " .. selection.Name)
	
	-- Define active tabs only: Esp and Misc
	local tabs = {
		Esp  = {buttonName = "Esp",  frameName = "EspFrame"},
		Misc = {buttonName = "Misc", frameName = "MiscFrame"},
	}
	
	-- Prepare storage
	local activeKey
	local defaultStrokes = {}
	
	-- Initialize each tab
	for key, def in pairs(tabs) do
		local btn = selection:FindFirstChild(def.buttonName)
		if not btn or not btn:IsA("TextButton") then
			warn(string.format("[UISelectionController] ERROR: %s button '%s' not found or not a TextButton", key, def.buttonName))
		else
			print(string.format("[UISelectionController] Found button '%s' for %s", def.buttonName, key))
		end
	
		local frm = sigma:FindFirstChild(def.frameName)
		if not frm or not frm:IsA("Frame") then
			warn(string.format("[UISelectionController] ERROR: %s frame '%s' not found or not a Frame", key, def.frameName))
		else
			print(string.format("[UISelectionController] Found frame '%s' for %s", def.frameName, key))
		end
	
		local stroke = btn:FindFirstChildOfClass("UIStroke") or Instance.new("UIStroke", btn)
		defaultStrokes[key] = stroke.Color
	
		if frm then frm.Visible = false end
	
		def.button = btn
		def.frame  = frm
		def.stroke = stroke
	end
	
	-- Tab switch function
	local function switchTo(key)
		print("[UISelectionController] switchTo called for " .. key)
		if activeKey and tabs[activeKey].stroke then
			tabs[activeKey].stroke.Color = defaultStrokes[activeKey]
			if tabs[activeKey].frame then tabs[activeKey].frame.Visible = false end
			print("[UISelectionController] Hiding frame for " .. activeKey)
		end
	
		local current = tabs[key]
		if not current then
			warn("[UISelectionController] ERROR: No tab definition for key " .. key)
			return
		end
		current.stroke.Color = Color3.new(1, 0, 0)
		if current.frame then current.frame.Visible = true end
		print("[UISelectionController] Showing frame for " .. key)
		activeKey = key
	end
	
	-- Connect tab buttons
	for key, def in pairs(tabs) do
		if def.button then
			def.button.Activated:Connect(function()
				print("[UISelectionController] Button " .. def.buttonName .. " activated")
				switchTo(key)
			end)
			print("[UISelectionController] Connected Activated for " .. def.buttonName)
		end
	end
	
	-- Auto-open Esp tab
	switchTo("Esp")
	
end;
task.spawn(C_52);

return G2L["1"], require;
