game:IsLoaded()
local hui = gethui()
local CoreGui = game:GetService("CoreGui")
local RobloxGui = CoreGui:FindFirstChild("RobloxGui")
local children = hui:GetChildren()
for k, v in children do
	v.Name:find("^FluentRenewed_Gatlify Error")
	local descendants = v:GetDescendants()
	for k2, v2 in descendants do
		v2.Visible = false
		v2:Destroy()
	end
	v:Destroy()
end
local children2 = CoreGui:GetChildren()
for k3, v3 in children2 do
	v3.Name:find("^FluentRenewed_Gatlify Error")
	local descendants2 = v3:GetDescendants()
	for k4, v4 in descendants2 do
		v4.Visible = false
		v4:Destroy()
	end
	v3:Destroy()
end
local children3 = RobloxGui:GetChildren()
for k5, v5 in children3 do
	v5.Name:find("^FluentRenewed_Gatlify Error")
	local descendants3 = v5:GetDescendants()
	for k6, v6 in descendants3 do
		v6.Visible = false
		v6:Destroy()
	end
	v5:Destroy()
end
local response = game:HttpGet("https://jnkie.com/sdk/library.lua")
local result = loadstring(response)()
result.service = "Gatlify"
result.identifier = "1054182"
local response2 = game:HttpGet("https://github.com/ActualMasterOogway/Fluent-Renewed/releases/latest/download/Fluent.luau")
local result2 = loadstring(response2)()
local UserInputService = game:GetService("UserInputService")
UserInputService:GetPlatform()
local Window = result2:CreateWindow({
	Title = "Gatlify",
	Acrylic = true,
	MinimizeKey = Enum.KeyCode.RightControl,
	Mobile = {
		Size = UDim2.fromOffset(50, 50),
		GetIcon = function(arg, arg2)
		end
	},
	Size = UDim2.fromOffset(580, 460),
	SubTitle = "",
	TabWidth = 140,
	Theme = "Dark"
})
getgenv().KEY_SYSTEM_LOADING = true
getgenv().GatlifyKeySystemLoading = true
getgenv().GatlifyLoaderWindow = Window
getgenv().GatlifyLoaderFluent = result2
getgenv().GatlifyKeySystemLoading = false
getgenv().KEY_SYSTEM_LOADING = false
getgenv().GatlifyLoaderFluent = nil
getgenv().GatlifyLoaderCleanup = function(arg3, arg4)
	local hui2 = gethui()
	local RobloxGui2 = CoreGui:FindFirstChild("RobloxGui")
	local children4 = hui2:GetChildren()
	for k7, v7 in children4 do
		v7.Name:find("^FluentRenewed_Gatlify Error")
		local descendants4 = v7:GetDescendants()
		for k8, v8 in descendants4 do
			v8.Visible = false
			v8:Destroy()
		end
		v7:Destroy()
	end
	local children5 = CoreGui:GetChildren()
	for k9, v9 in children5 do
		v9.Name:find("^FluentRenewed_Gatlify Error")
		local descendants5 = v9:GetDescendants()
		for k10, v10 in descendants5 do
			v10.Visible = false
			v10:Destroy()
		end
		v9:Destroy()
	end
	local children6 = RobloxGui2:GetChildren()
	for k11, v11 in children6 do
		v11.Name:find("^FluentRenewed_Gatlify Error")
		local descendants6 = v11:GetDescendants()
		for k12, v12 in descendants6 do
			v12.Visible = false
			v12:Destroy()
		end
		v11:Destroy()
	end
	Window:Destroy()
	getgenv().GatlifyLoaderWindow = nil
	result2:Destroy()
end
local Tab = Window:AddTab({ Title = "Key", Icon = "key-round" })
local UIListLayout = Tab.ContainerFrame:FindFirstChildWhichIsA("UIListLayout")
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
local Paragraph = Tab:AddParagraph("RequiredKey", { Title = "Key Required", Content = "Please provide your key to gain access." })
Paragraph.Frame.LayoutOrder = 1
local Button = Tab:AddButton({
	Title = "Get key",
	Description = "",
	Callback = function(state, arg6)
		setclipboard("https://jnkie.com/get-key/gatlify")
		result2:Notify({ Title = "Success", Content = "Key link copied to clipboard!", Duration = 4 })
	end
})
Button.Frame.LayoutOrder = 2
local Paragraph2 = Tab:AddParagraph("PremiumNotice", {
	Title = "Tired of Daily Keys?",
	Content = "You can purchase a weekly, monthly, or permanent premium key to bypass daily key system entirely."
})
Paragraph2.Frame.LayoutOrder = 3
local Button2 = Tab:AddButton({
	Title = "Purchase Premium",
	Description = "Copy store link to clipboard",
	Callback = function(state, arg8)
		setclipboard("https://gatlify.mysellauth.com/product/gatlify")
		result2:Notify({ Title = "Success", Content = "Store link copied to clipboard!", Duration = 4 })
	end
})
Button2.Frame.LayoutOrder = 4
local Input = Tab:AddInput("KeyField", {
	Title = "Enter Key",
	Placeholder = "Paste key here...",
	Callback = function(state, arg10)
	end
})
Input.Frame.LayoutOrder = 5
local Button3 = Tab:AddButton({
	Title = "Verify key",
	Description = "",
	Callback = function(state, arg12)
		result2:Notify({ Title = "Validation Failed", Content = "Key cannot be empty", Duration = 5 })
	end
})
Button3.Frame.LayoutOrder = 6
Window:SelectTab(1)
task.wait(0.1)
task.wait(0.1)
