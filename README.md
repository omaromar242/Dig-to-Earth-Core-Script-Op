--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 77 | Scripts: 20 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.omarDigToEarthCore
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["DisplayOrder"] = 1000;
G2L["1"]["Name"] = [[omarDigToEarthCore]];


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
G2L["8"]["Position"] = UDim2.new(0.11248, 0, 0.49655, 0);


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
G2L["d"]["CursorPosition"] = -1;
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
G2L["d"]["Position"] = UDim2.new(0.0037, 0, 0.05029, 0);
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
G2L["10"]["Position"] = UDim2.new(0.07914, 0, 0.69997, 0);


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
G2L["16"]["CursorPosition"] = -1;
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
G2L["16"]["Position"] = UDim2.new(0.0037, 0, 0.1991, 0);
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
G2L["19"]["CursorPosition"] = -1;
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
G2L["19"]["Position"] = UDim2.new(-0.0037, 0, 0.34196, 0);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[]];


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch3.UICorner
G2L["1a"] = Instance.new("UICorner", G2L["19"]);
G2L["1a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.EspFrame.Howmuch3.UIStroke
G2L["1b"] = Instance.new("UIStroke", G2L["19"]);
G2L["1b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1b"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.drag localscript
G2L["1c"] = Instance.new("LocalScript", G2L["2"]);
G2L["1c"]["Name"] = [[drag localscript]];


-- StarterGui.omarDigToEarthCore.sigma.Selection
G2L["1d"] = Instance.new("Frame", G2L["2"]);
G2L["1d"]["Active"] = true;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(78, 78, 78);
G2L["1d"]["Size"] = UDim2.new(0.2198, 0, 1, 0);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Name"] = [[Selection]];


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp
G2L["1e"] = Instance.new("TextButton", G2L["1d"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["1e"]["Name"] = [[Esp]];
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Main]];
G2L["1e"]["Position"] = UDim2.new(0.07176, 0, 0.05268, 0);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Esp.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1e"]);
G2L["20"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["20"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.Selection.UICorner
G2L["21"] = Instance.new("UICorner", G2L["1d"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.UIStroke
G2L["22"] = Instance.new("UIStroke", G2L["1d"]);
G2L["22"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["22"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc
G2L["23"] = Instance.new("TextButton", G2L["1d"]);
G2L["23"]["TextWrapped"] = true;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextScaled"] = true;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["23"]["Name"] = [[Misc]];
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Text"] = [[Misc]];
G2L["23"]["Position"] = UDim2.new(0.07176, 0, 0.28213, 0);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc.UICorner
G2L["24"] = Instance.new("UICorner", G2L["23"]);
G2L["24"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.Selection.Misc.UIStroke
G2L["25"] = Instance.new("UIStroke", G2L["23"]);
G2L["25"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["25"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame
G2L["26"] = Instance.new("Frame", G2L["2"]);
G2L["26"]["Visible"] = false;
G2L["26"]["Active"] = true;
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["26"]["Size"] = UDim2.new(0.76082, 0, 1, 0);
G2L["26"]["Position"] = UDim2.new(0.23918, 0, 0, 0);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Name"] = [[MiscFrame]];
G2L["26"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.UIStroke
G2L["27"] = Instance.new("UIStroke", G2L["26"]);
G2L["27"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["27"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.UICorner
G2L["28"] = Instance.new("UICorner", G2L["26"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four
G2L["29"] = Instance.new("TextButton", G2L["26"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["Size"] = UDim2.new(0.76178, 0, 0.14432, 0);
G2L["29"]["Name"] = [[four]];
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[Buy Best Pickaxe]];
G2L["29"]["Position"] = UDim2.new(0.12138, 0, 0.0505, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.UIStroke
G2L["2b"] = Instance.new("UIStroke", G2L["29"]);
G2L["2b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2b"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.soundclick
G2L["2c"] = Instance.new("LocalScript", G2L["29"]);
G2L["2c"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.LocalScript
G2L["2d"] = Instance.new("LocalScript", G2L["29"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag
G2L["2e"] = Instance.new("TextButton", G2L["26"]);
G2L["2e"]["TextWrapped"] = true;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextScaled"] = true;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["Size"] = UDim2.new(0.75267, 0, 0.09669, 0);
G2L["2e"]["Name"] = [[antilag]];
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Text"] = [[Fps Booster]];
G2L["2e"]["Position"] = UDim2.new(0.12974, 0, 0.39759, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.UICorner
G2L["2f"] = Instance.new("UICorner", G2L["2e"]);
G2L["2f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.UIStroke
G2L["30"] = Instance.new("UIStroke", G2L["2e"]);
G2L["30"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["30"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.soundclick
G2L["31"] = Instance.new("LocalScript", G2L["2e"]);
G2L["31"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Link
G2L["33"] = Instance.new("TextLabel", G2L["26"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Size"] = UDim2.new(0.80019, 0, 0.11608, 0);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[https://discord.gg/HJSfaPTDCX]];
G2L["33"]["Name"] = [[Link]];
G2L["33"]["Position"] = UDim2.new(-0.01336, 0, 0.69759, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy
G2L["34"] = Instance.new("TextButton", G2L["26"]);
G2L["34"]["TextWrapped"] = true;
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["TextSize"] = 14;
G2L["34"]["TextScaled"] = true;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["34"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["34"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["34"]["Name"] = [[Copy]];
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["Text"] = [[COPY]];
G2L["34"]["Position"] = UDim2.new(0.78383, 0, 0.69484, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UICorner
G2L["35"] = Instance.new("UICorner", G2L["34"]);
G2L["35"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UIStroke
G2L["36"] = Instance.new("UIStroke", G2L["34"]);
G2L["36"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["36"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["34"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
G2L["38"] = Instance.new("LocalScript", G2L["34"]);
G2L["38"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.subto
G2L["39"] = Instance.new("TextLabel", G2L["26"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextScaled"] = true;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["BackgroundTransparency"] = 1;
G2L["39"]["Size"] = UDim2.new(0.67369, 0, 0.12617, 0);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[Channel: omargamer8198]];
G2L["39"]["Name"] = [[subto]];
G2L["39"]["Position"] = UDim2.new(0.05281, 0, 0.84852, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy
G2L["3a"] = Instance.new("TextButton", G2L["26"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["3a"]["Name"] = [[Copy]];
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[COPY]];
G2L["3a"]["Position"] = UDim2.new(0.72585, 0, 0.87069, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["3a"]);
G2L["3b"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["3a"]);
G2L["3c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3c"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
G2L["3d"] = Instance.new("LocalScript", G2L["3a"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
G2L["3e"] = Instance.new("LocalScript", G2L["3a"]);
G2L["3e"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk
G2L["3f"] = Instance.new("TextButton", G2L["26"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["3f"]["Name"] = [[AntiAfk]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[AntiAfk]];
G2L["3f"]["Position"] = UDim2.new(0.12138, 0, 0.52625, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.UICorner
G2L["40"] = Instance.new("UICorner", G2L["3f"]);
G2L["40"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.UIStroke
G2L["41"] = Instance.new("UIStroke", G2L["3f"]);
G2L["41"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["41"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.soundclick
G2L["42"] = Instance.new("LocalScript", G2L["3f"]);
G2L["42"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.LocalScript
G2L["43"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five
G2L["44"] = Instance.new("TextButton", G2L["26"]);
G2L["44"]["TextWrapped"] = true;
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["TextSize"] = 14;
G2L["44"]["TextScaled"] = true;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["44"]["Size"] = UDim2.new(0.76178, 0, 0.14432, 0);
G2L["44"]["Name"] = [[five]];
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[Auto Chest]];
G2L["44"]["Position"] = UDim2.new(0.12508, 0, 0.22609, 0);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.UICorner
G2L["45"] = Instance.new("UICorner", G2L["44"]);
G2L["45"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.UIStroke
G2L["46"] = Instance.new("UIStroke", G2L["44"]);
G2L["46"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["46"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.soundclick
G2L["47"] = Instance.new("LocalScript", G2L["44"]);
G2L["47"]["Name"] = [[soundclick]];


-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["44"]);



-- StarterGui.omarDigToEarthCore.Toggle
G2L["49"] = Instance.new("TextButton", G2L["1"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0.04464, 0, 0.0641, 0);
G2L["49"]["Name"] = [[Toggle]];
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Hide]];
G2L["49"]["Position"] = UDim2.new(0.11384, 0, 0.02595, 0);


-- StarterGui.omarDigToEarthCore.Toggle.UICorner
G2L["4a"] = Instance.new("UICorner", G2L["49"]);
G2L["4a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarDigToEarthCore.Toggle.LocalScript
G2L["4b"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.omarDigToEarthCore.Toggle.UIStroke
G2L["4c"] = Instance.new("UIStroke", G2L["49"]);
G2L["4c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4c"]["Thickness"] = 3;


-- StarterGui.omarDigToEarthCore.Changer
G2L["4d"] = Instance.new("LocalScript", G2L["1"]);
G2L["4d"]["Name"] = [[Changer]];


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
	
	-- Validate numeric text
	local function isValidNumber(text)
		local n = tonumber(text)
		return n and n > 0
	end
	
	-- Handler
	sendButton.Activated:Connect(function()
		print("[LocalScript] Button 'first' activated")       -- DEBUG
		print("[LocalScript] CashBox.Text:", cashBox.Text)    -- DEBUG
		print("[LocalScript] GemsBox.Text:", gemsBox.Text)    -- DEBUG
		print("[LocalScript] SpinsBox.Text:", spinsBox.Text)  -- DEBUG
	
		-- Cash
		if isValidNumber(cashBox.Text) then
			local amt = tonumber(cashBox.Text)
			print("[LocalScript] Sending Cash:", amt)         -- DEBUG
			AddRewardEvent:FireServer("Cash", amt)
		else
			warn("[LocalScript] Invalid Cash input, skipping")
		end
	
		-- Gems
		if isValidNumber(gemsBox.Text) then
			local amt = tonumber(gemsBox.Text)
			print("[LocalScript] Sending Gems:", amt)         -- DEBUG
			AddRewardEvent:FireServer("Gems", amt)
		else
			warn("[LocalScript] Invalid Gems input, skipping")
		end
	
		-- Spins
		if isValidNumber(spinsBox.Text) then
			local amt = tonumber(spinsBox.Text)
			print("[LocalScript] Sending Spins:", amt)        -- DEBUG
			AddRewardEvent:FireServer("Spins", amt)
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
-- StarterGui.omarDigToEarthCore.sigma.drag localscript
local function C_1c()
local script = G2L["1c"];
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
task.spawn(C_1c);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.soundclick
local function C_2c()
local script = G2L["2c"];
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
task.spawn(C_2c);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.four.LocalScript
local function C_2d()
local script = G2L["2d"];
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
task.spawn(C_2d);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.soundclick
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
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.antilag.LocalScript
local function C_32()
local script = G2L["32"];
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
task.spawn(C_32);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
local function C_37()
local script = G2L["37"];
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
task.spawn(C_37);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
local function C_38()
local script = G2L["38"];
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
task.spawn(C_38);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.LocalScript
local function C_3d()
local script = G2L["3d"];
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
task.spawn(C_3d);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.Copy.soundclick
local function C_3e()
local script = G2L["3e"];
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
task.spawn(C_3e);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.soundclick
local function C_42()
local script = G2L["42"];
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
task.spawn(C_42);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.AntiAfk.LocalScript
local function C_43()
local script = G2L["43"];
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
task.spawn(C_43);
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.soundclick
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
-- StarterGui.omarDigToEarthCore.sigma.MiscFrame.five.LocalScript
local function C_48()
local script = G2L["48"];
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
task.spawn(C_48);
-- StarterGui.omarDigToEarthCore.Toggle.LocalScript
local function C_4b()
local script = G2L["4b"];
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
task.spawn(C_4b);
-- StarterGui.omarDigToEarthCore.Changer
local function C_4d()
local script = G2L["4d"];
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
task.spawn(C_4d);

return G2L["1"], require;
