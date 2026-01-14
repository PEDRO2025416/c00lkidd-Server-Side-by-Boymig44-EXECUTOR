--[=[

d888b  db    db d888888b      .d888b.      db      db    db  .d8b.

88' Y8b 88    88   88'        VP  8D      88      88    88 d8' `8b

88      88    88    88            odD'      88      88    88 88ooo88

88  ooo 88    88    88          .88'        88      88    88 88~~~88

88.  88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev



Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER

]=]

-- Instances: 16 | Scripts: 5 | Modules: 0 | Tags: 0

local G2L = {};

-- StarterGui.c00lkidd executor

G2L["1"] = Instance.new("ScreenGui", game:GetService("CoreGui"):WaitForChild("RobloxGui"));

G2L["1"]["Name"] = [[c00lkidd executor]];

G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

G2L["1"]["ResetOnSpawn"] = false;

-- StarterGui.c00lkidd executor.Frame

G2L["2"] = Instance.new("Frame", G2L["1"]);

G2L["2"]["Active"] = true;

G2L["2"]["BorderSizePixel"] = 3;

G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["2"]["Selectable"] = true;

G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);

G2L["2"]["Size"] = UDim2.new(0, 640, 0, 310);

G2L["2"]["Position"] = UDim2.new(0.5, 26, 0.5, 22);

G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 0, 0);

G2L["2"]["BackgroundTransparency"] = 0.5;

-- StarterGui.c00lkidd executor.Frame.UIScale

G2L["3"] = Instance.new("UIScale", G2L["2"]);

-- StarterGui.c00lkidd executor.Frame.c00lkidd image

G2L["4"] = Instance.new("ImageLabel", G2L["2"]);

G2L["4"]["BorderSizePixel"] = 0;

G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);

G2L["4"]["Image"] = [[rbxassetid://96083365637107]];

G2L["4"]["Size"] = UDim2.new(0, 240, 0, 226);

G2L["4"]["BackgroundTransparency"] = 1;

G2L["4"]["Rotation"] = 14;

G2L["4"]["Name"] = [[c00lkidd image]];

G2L["4"]["Position"] = UDim2.new(0.599, 0, -0.188, 0);

-- StarterGui.c00lkidd executor.Frame.Auto Username Fill

G2L["5"] = Instance.new("TextButton", G2L["2"]);

G2L["5"]["TextWrapped"] = true;

G2L["5"]["BorderSizePixel"] = 2;

G2L["5"]["TextScaled"] = true;

G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["5"]["BackgroundColor3"] = Color3.fromRGB(13, 90, 0);

G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["5"]["Size"] = UDim2.new(0, 137, 0, 28);

G2L["5"]["BorderColor3"] = Color3.fromRGB(155, 55, 55);

G2L["5"]["Text"] = [[Auto Username Fill]];

G2L["5"]["Name"] = [[Auto Username Fill]];

G2L["5"]["Position"] = UDim2.new(0.02, 0, 0.019, 0);

-- StarterGui.c00lkidd executor.Frame.Auto Username Fill.LocalScript

G2L["6"] = Instance.new("LocalScript", G2L["5"]);

-- StarterGui.c00lkidd executor.Frame.Execute

G2L["7"] = Instance.new("TextButton", G2L["2"]);

G2L["7"]["TextWrapped"] = true;

G2L["7"]["BorderSizePixel"] = 2;

G2L["7"]["TextScaled"] = true;

G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["7"]["Size"] = UDim2.new(0, 137, 0, 28);

G2L["7"]["BorderColor3"] = Color3.fromRGB(155, 55, 55);

G2L["7"]["Text"] = [[Execute]];

G2L["7"]["Name"] = [[Execute]];

G2L["7"]["Position"] = UDim2.new(0.02, 0, 0.887, 0);

-- StarterGui.c00lkidd executor.Frame.Clear

G2L["8"] = Instance.new("TextButton", G2L["2"]);

G2L["8"]["TextWrapped"] = true;

G2L["8"]["BorderSizePixel"] = 2;

G2L["8"]["TextScaled"] = true;

G2L["8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["8"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["8"]["Size"] = UDim2.new(0, 137, 0, 28);

G2L["8"]["BorderColor3"] = Color3.fromRGB(155, 55, 55);

G2L["8"]["Text"] = [[Clear]];

G2L["8"]["Name"] = [[Clear]];

G2L["8"]["Position"] = UDim2.new(0.266, 0, 0.887, 0);

-- StarterGui.c00lkidd executor.Frame.Clear.LocalScript

G2L["9"] = Instance.new("LocalScript", G2L["8"]);

-- StarterGui.c00lkidd executor.Frame.infect

G2L["a"] = Instance.new("TextButton", G2L["2"]);

G2L["a"]["TextWrapped"] = true;

G2L["a"]["BorderSizePixel"] = 2;

G2L["a"]["TextScaled"] = true;

G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["a"]["Size"] = UDim2.new(0, 100, 0, 28);

G2L["a"]["BorderColor3"] = Color3.fromRGB(155, 55, 55);

G2L["a"]["Text"] = [[Infect]];

G2L["a"]["Name"] = [[infect]];

G2L["a"]["Position"] = UDim2.new(0.818, 0, 0.887, 0);

-- StarterGui.c00lkidd executor.Frame.Reset

G2L["b"] = Instance.new("TextButton", G2L["2"]);

G2L["b"]["TextWrapped"] = true;

G2L["b"]["BorderSizePixel"] = 2;

G2L["b"]["TextScaled"] = true;

G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["b"]["Size"] = UDim2.new(0, 100, 0, 28);

G2L["b"]["BorderColor3"] = Color3.fromRGB(155, 55, 55);

G2L["b"]["Text"] = [[Reset Character]];

G2L["b"]["Name"] = [[Reset]];

G2L["b"]["Position"] = UDim2.new(0.64, 0, 0.887, 0);

-- StarterGui.c00lkidd executor.Frame.Reset.LocalScript

G2L["c"] = Instance.new("LocalScript", G2L["b"]);

-- StarterGui.c00lkidd executor.Frame.c00lkidd text

G2L["d"] = Instance.new("TextLabel", G2L["2"]);

G2L["d"]["TextWrapped"] = true;

G2L["d"]["TextScaled"] = true;

G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);

G2L["d"]["BackgroundTransparency"] = 1;

G2L["d"]["Size"] = UDim2.new(0, 200, 0, 40);

G2L["d"]["Text"] = [[c00lkidd 2025 SS]];

G2L["d"]["Name"] = [[c00lkidd text]];

G2L["d"]["Position"] = UDim2.new(0.45, 0, 0, 0);

-- StarterGui.c00lkidd executor.Frame.CodeBox

G2L["e"] = Instance.new("TextBox", G2L["2"]);

G2L["e"]["CursorPosition"] = -1;

G2L["e"]["Name"] = [[CodeBox]];

G2L["e"]["TextXAlignment"] = Enum.TextXAlignment.Left;

G2L["e"]["BorderSizePixel"] = 0;

G2L["e"]["TextWrapped"] = true;

G2L["e"]["TextSize"] = 14;

G2L["e"]["TextColor3"] = Color3.fromRGB(171, 171, 171);

G2L["e"]["TextYAlignment"] = Enum.TextYAlignment.Top;

G2L["e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);

G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);

G2L["e"]["MultiLine"] = true;

G2L["e"]["ClearTextOnFocus"] = false;

G2L["e"]["Size"] = UDim2.new(0.954, 0, 0.72258, 0);

G2L["e"]["Position"] = UDim2.new(0.02, 0, 0.12903, 0);

G2L["e"]["Text"] = [[made by rtls_a1 on discord. SS by Boymig44!]];

-- StarterGui.c00lkidd executor.Module

G2L["f"] = Instance.new("LocalScript", G2L["1"]);

G2L["f"]["Name"] = [[Module]];

-- StarterGui.c00lkidd executor.Drag

G2L["10"] = Instance.new("LocalScript", G2L["1"]);

G2L["10"]["Name"] = [[Drag]];

-- StarterGui.c00lkidd executor.Frame.Auto Username Fill.LocalScript

local function C_6()

local script = G2L["6"];

local button = script.Parent

local textBox = button.Parent:WaitForChild("CodeBox")



button.MouseButton1Click:Connect(function()

	local player = game.Players.LocalPlayer

	local nome = player.Name

	local texto = textBox.Text



	-- 1. Tenta substituir o que estiver entre aspas duplas: "qualquer coisa" -> "Nome"

	local novoTexto = string.gsub(texto, '"(.-)"', '"' .. nome .. '"')



	-- 2. Tenta substituir o que estiver entre aspas simples: 'qualquer coisa' -> 'Nome'

	novoTexto = string.gsub(novoTexto, "'(.-)'", "'" .. nome .. "'")



	textBox.Text = novoTexto

end)

end;

task.spawn(C_6);

-- StarterGui.c00lkidd executor.Frame.Clear.LocalScript

local function C_9()

local script = G2L["9"];

local botao = script.Parent

-- Altere o caminho abaixo se a sua TextBox tiver outro nome ou estiver em outro lugar

local textBox = botao.Parent:WaitForChild("CodeBox") 



botao.MouseButton1Click:Connect(function()

	textBox.Text = "" -- Isso define o texto como vazio

end)

end;

task.spawn(C_9);

-- StarterGui.c00lkidd executor.Frame.Reset.LocalScript

local function C_c()

local script = G2L["c"];

local botao = script.Parent

local player = game.Players.LocalPlayer



botao.MouseButton1Click:Connect(function()

	-- Verifica se o personagem existe antes de tentar matar

	local personagem = player.Character

	if personagem then

		local humanoid = personagem:FindFirstChild("Humanoid")

		if humanoid then

			humanoid.Health = 0

		end

	end

end)

end;

task.spawn(C_c);

-- StarterGui.c00lkidd executor.Module

local function C_f()

local script = G2L["f"];

local UIS = game:GetService("UserInputService")

local MainFrame = script.Parent.Parent

local CodeBox = MainFrame:FindFirstChild("CodeBox", true)

local ExecBtn = MainFrame:FindFirstChild("Execute", true)

local InfectBtn = MainFrame:FindFirstChild("infect", true)



-- LÓGICA DE TESTE DO IGA HUB (O QUE NÃO KICKA)

local function testRemote(r)

	local uniqueName = "IGA_TEST_" .. math.random(1000000, 9999999)

	local uniqueValue = tostring(math.random(100000, 999999))



	-- Payload de teste idêntico ao IGA

	local payload = [[

        local marker = Instance.new("StringValue")

        marker.Name = "]] .. uniqueName .. [["

        marker.Value = "]] .. uniqueValue .. [["

        marker.Parent = game:GetService("Workspace")

    ]]



	pcall(function()

		if r:IsA("RemoteEvent") then

			r:FireServer(payload)

		elseif r:IsA("RemoteFunction") then

			r:InvokeServer(payload)

		end

	end)



	-- Espera a confirmação (igual ao IGA Hub)

	for i = 1, 20 do

		task.wait(0.1)

		local marker = game.Workspace:FindFirstChild(uniqueName)

		if marker and marker.Value == uniqueValue then

			marker:Destroy()

			return true

		end

	end

	return false

end



-- Botão INFECT (Scanner do IGA)

InfectBtn.MouseButton1Click:Connect(function()

	InfectBtn.Text = "INFECTING..."

	local found = {}



	-- Containers que o IGA varre

	local containers = {game:GetService("ReplicatedStorage"), game:GetService("Workspace"), game:GetService("Lighting"), game}



	for _, container in ipairs(containers) do

		for _, obj in pairs(container:GetDescendants()) do

			-- Filtros de segurança do IGA

			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) then

				if not obj:GetFullName():find("RobloxReplicatedStorage") and not obj.Name:find("__") then

					if testRemote(obj) then

						table.insert(found, obj)

					end

				end

			end

		end

	end



	_G.TargetRemotes = found

	InfectBtn.Text = "Founded: " .. #found

	CodeBox.Visible, ExecBtn.Visible = true, true

end)



-- Botão EXECUTE (Envio direto do IGA)

ExecBtn.MouseButton1Click:Connect(function()

	local code = CodeBox.Text

	if not code or not _G.TargetRemotes then return end



	for _, r in pairs(_G.TargetRemotes) do

		pcall(function()

			if r:IsA("RemoteEvent") then

				r:FireServer(code)

			else

				r:InvokeServer(code)

			end

		end)

	end



	ExecBtn.Text = "Executed!"

	task.wait(1)

	ExecBtn.Text = "Execute"

end)



UIS.InputBegan:Connect(function(i, p) if not p and i.KeyCode == Enum.KeyCode.J then MainFrame.Visible = not MainFrame.Visible end end)

end;

task.spawn(C_f);

-- StarterGui.c00lkidd executor.Drag

local function C_10()

local script = G2L["10"];

local UIS = game:GetService("UserInputService")

local TweenService = game:GetService("TweenService")



local function makeDraggable(frame)

	local dragging = false

	local dragInput

	local dragStart

	local startPos



	-- Função que calcula a nova posição e suaviza o movimento

	local function update(input)

		local delta = input.Position - dragStart

		local targetPos = UDim2.new(

			startPos.X.Scale, 

			startPos.X.Offset + delta.X, 

			startPos.Y.Scale, 

			startPos.Y.Offset + delta.Y

		)



		-- Cria o efeito de deslizamento suave

		TweenService:Create(frame, TweenInfo.new(0.15), {Position = targetPos}):Play()

	end



	-- Quando você clica no Frame

	frame.InputBegan:Connect(function(input)

		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then

			dragging = true

			dragStart = input.Position

			startPos = frame.Position



			-- Detecta quando você solta o clique

			input.Changed:Connect(function()

				if input.UserInputState == Enum.UserInputState.End then

					dragging = false

				end

			end)

		end

	end)



	-- Quando você move o mouse/dedo

	frame.InputChanged:Connect(function(input)

		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then

			dragInput = input

		end

	end)



	-- O loop que atualiza a posição enquanto você arrasta

	UIS.InputChanged:Connect(function(input)

		if input == dragInput and dragging then

			update(input)

		end

	end)

end



-- Como usar:

makeDraggable(script.Parent.Frame)

end;

task.spawn(C_10);

return G2L["1"], require;
