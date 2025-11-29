if game.PlaceId == 2753915549 then
    Mundo1 = true
elseif game.PlaceId == 4442272183 then
    Mundo2 = true
elseif game.PlaceId == 7449423635 then
    Mundo3 = true
else
    game:GetService("Players").LocalPlayer:Kick("Não suportado, por favor aguarde...")
end
function VerificarMissao() 
    MeuNivel = game:GetService("Players").LocalPlayer.Data.Level.Value
    
    if Mundo1 then
        if MeuNivel >= 1 and MeuNivel <= 9 then
            Mob = "Bandido"
            NivelMissao = 1
            NomeMissao = "BanditQuest1"
            NomeMob = "Bandit"
            CFrameMissao = CFrame.new(1059.37, 15.45, 1550.42)
            CFrameMob = CFrame.new(1045.96, 27.00, 1560.82)

        elseif MeuNivel >= 10 and MeuNivel <= 14 then
            Mob = "Macaco"
            NivelMissao = 1
            NomeMissao = "JungleQuest"
            NomeMob = "Monkey"
            CFrameMissao = CFrame.new(-1598.08, 35.55, 153.37)
            CFrameMob = CFrame.new(-1448.51, 67.85, 11.46)

        elseif MeuNivel >= 15 and MeuNivel <= 29 then
            Mob = "Gorila"
            NivelMissao = 2
            NomeMissao = "JungleQuest"
            NomeMob = "Gorilla"
            CFrameMissao = CFrame.new(-1598.08, 35.55, 153.37)
            CFrameMob = CFrame.new(-1129.88, 40.46, -525.42)

        elseif MeuNivel >= 30 and MeuNivel <= 39 then
            Mob = "Pirata"
            NivelMissao = 1
            NomeMissao = "BuggyQuest1"
            NomeMob = "Pirate"
            CFrameMissao = CFrame.new(-1141.07, 4.10, 3831.54)
            CFrameMob = CFrame.new(-1103.51, 13.75, 3896.09)
        elseif MeuNivel >= 40 and MeuNivel <= 59 then
            Mob = "Brutamonte"
            NivelMissao = 2
            NomeMissao = "BuggyQuest1"
            NomeMob = "Brute"
            CFrameMissao = CFrame.new(-1141.07, 4.10, 3831.54)
            CFrameMob = CFrame.new(-1140.08, 14.80, 4322.92)

        elseif MeuNivel >= 60 and MeuNivel <= 74 then
            Mob = "Bandido do Deserto"
            NivelMissao = 1
            NomeMissao = "DesertQuest"
            NomeMob = "Desert Bandit"
            CFrameMissao = CFrame.new(894.48, 5.14, 4392.43)
            CFrameMob = CFrame.new(924.79, 6.44, 4481.58)

        elseif MeuNivel >= 75 and MeuNivel <= 89 then
            Mob = "Oficial do Deserto"
            NivelMissao = 2
            NomeMissao = "DesertQuest"
            NomeMob = "Desert Officer"
            CFrameMissao = CFrame.new(894.48, 5.14, 4392.43)
            CFrameMob = CFrame.new(1608.28, 8.61, 4371.00)

        elseif MeuNivel >= 90 and MeuNivel <= 99 then
            Mob = "Bandido da Neve"
            NivelMissao = 1
            NomeMissao = "SnowQuest"
            NomeMob = "Snow Bandit"
            CFrameMissao = CFrame.new(1389.74, 88.15, -1298.90)
            CFrameMob = CFrame.new(1354.34, 87.27, -1393.94)

        elseif MeuNivel >= 100 and MeuNivel <= 119 then
            Mob = "Homem de Neve"
            NivelMissao = 2
            NomeMissao = "SnowQuest"
            NomeMob = "Snowman"
            CFrameMissao = CFrame.new(1389.74, 88.15, -1298.90)
            CFrameMob = CFrame.new(1201.64, 144.57, -1550.06)

        elseif MeuNivel >= 120 and MeuNivel <= 149 then
            Mob = "Suboficial Chefe"
            NivelMissao = 1
            NomeMissao = "MarineQuest2"
            NomeMob = "Chief Petty Officer"
            CFrameMissao = CFrame.new(-5039.58, 27.35, 4324.68)
            CFrameMob = CFrame.new(-4881.23, 22.65, 4273.75)

        elseif MeuNivel >= 150 and MeuNivel <= 174 then
            Mob = "Bandido do Céu"
            NivelMissao = 1
            NomeMissao = "SkyQuest"
            NomeMob = "Sky Bandit"
            CFrameMissao = CFrame.new(-4839.53, 716.36, -2619.44)
            CFrameMob = CFrame.new(-4953.20, 295.74, -2899.22)

        elseif MeuNivel >= 175 and MeuNivel <= 189 then
            Mob = "Mestre das Sombras"
            NivelMissao = 2
            NomeMissao = "SkyQuest"
            NomeMob = "Dark Master"
            CFrameMissao = CFrame.new(-4839.53, 716.36, -2619.44)
            CFrameMob = CFrame.new(-5259.84, 391.39, -2229.03)

        elseif MeuNivel >= 190 and MeuNivel <= 209 then
            Mob = "Prisioneiro"
            NivelMissao = 1
            NomeMissao = "PrisonerQuest"
            NomeMob = "Prisoner"
            CFrameMissao = CFrame.new(5308.93, 1.65, 475.12)
            CFrameMob = CFrame.new(5098.97, -0.32, 474.23)

        elseif MeuNivel >= 210 and MeuNivel <= 249 then
            Mob = "Prisioneiro Perigoso"
            NivelMissao = 2
            NomeMissao = "PrisonerQuest"
            NomeMob = "Dangerous Prisoner"
            CFrameMissao = CFrame.new(5308.93, 1.65, 475.12)
            CFrameMob = CFrame.new(5654.56, 15.63, 866.29)

        elseif MeuNivel >= 250 and MeuNivel <= 274 then
            Mob = "Guerreiro Toga"
            NivelMissao = 1
            NomeMissao = "ColosseumQuest"
            NomeMob = "Toga Warrior"
            CFrameMissao = CFrame.new(-1580.04, 6.35, -2986.47)
            CFrameMob = CFrame.new(-1820.21, 51.68, -2740.66)

        elseif MeuNivel >= 275 and MeuNivel <= 299 then
            Mob = "Gladiador"
            NivelMissao = 2
            NomeMissao = "ColosseumQuest"
            NomeMob = "Gladiator"
            CFrameMissao = CFrame.new(-1580.04, 6.35, -2986.47)
            CFrameMob = CFrame.new(-1292.83, 56.38, -3339.03)

        elseif MeuNivel >= 300 and MeuNivel <= 324 then
            Mob = "Soldado Militar"
            NivelMissao = 1
            NomeMissao = "MagmaQuest"
            NomeMob = "Military Soldier"
            CFrameMissao = CFrame.new(-5313.37, 10.95, 8515.29)
            CFrameMob = CFrame.new(-5411.16, 11.08, 8454.29)

        elseif MeuNivel >= 325 and MeuNivel <= 374 then
            Mob = "Espião Militar"
            NivelMissao = 2
            NomeMissao = "MagmaQuest"
            NomeMob = "Military Spy"
            CFrameMissao = CFrame.new(-5313.37, 10.95, 8515.29)
            CFrameMob = CFrame.new(-5802.86, 86.26, 8828.85)
        elseif MeuNivel >= 375 and MeuNivel <= 399 then
            Mob = "Guerreiro Tritão"
            NivelMissao = 1
            NomeMissao = "FishmanQuest"
            NomeMob = "Fishman Warrior"
            CFrameMissao = CFrame.new(61122.65, 18.49, 1569.39)
            CFrameMob = CFrame.new(60878.30, 18.48, 1543.75)
            if _G.AutoFarm and (CFrameMissao.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(
                    "requestEntrance",
                    Vector3.new(61163.85, 11.67, 1819.78)
                )
            end

        elseif MeuNivel >= 400 and MeuNivel <= 449 then
            Mob = "Comando Tritão"
            NivelMissao = 2
            NomeMissao = "FishmanQuest"
            NomeMob = "Fishman Commando"
            CFrameMissao = CFrame.new(61122.65, 18.49, 1569.39)
            CFrameMob = CFrame.new(61922.63, 18.48, 1493.93)
            if _G.AutoFarm and (CFrameMissao.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(
                    "requestEntrance",
                    Vector3.new(61163.85, 11.67, 1819.78)
                )
            end

        elseif MeuNivel >= 450 and MeuNivel <= 474 then
            Mob = "Guarda Divino"
            NivelMissao = 1
            NomeMissao = "SkyExp1Quest"
            NomeMob = "God's Guard"
            CFrameMissao = CFrame.new(-4721.88, 843.87, -1949.96)
            CFrameMob = CFrame.new(-4710.04, 845.27, -1927.30)
            if _G.AutoFarm and (CFrameMissao.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(
                    "requestEntrance",
                    Vector3.new(-4607.82, 872.54, -1667.55)
                )
            end

        elseif MeuNivel >= 475 and MeuNivel <= 524 then
            Mob = "Shanda"
            NivelMissao = 2
            NomeMissao = "SkyExp1Quest"
            NomeMob = "Shanda"
            CFrameMissao = CFrame.new(-7859.09, 5544.19, -381.47)
            CFrameMob = CFrame.new(-7678.48, 5566.40, -497.21)
            if _G.AutoFarm and (CFrameMissao.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(
                    "requestEntrance",
                    Vector3.new(-7894.61, 5547.14, -380.29)
                )
            end

        elseif MeuNivel >= 525 and MeuNivel <= 549 then
            Mob = "Esquadrão Real"
            NivelMissao = 1
            NomeMissao = "SkyExp2Quest"
            NomeMob = "Royal Squad"
            CFrameMissao = CFrame.new(-7906.81, 5634.66, -1411.99)
            CFrameMob = CFrame.new(-7624.25, 5658.13, -1467.35)

        elseif MeuNivel >= 550 and MeuNivel <= 624 then
            Mob = "Soldado Real"
            NivelMissao = 2
            NomeMissao = "SkyExp2Quest"
            NomeMob = "Royal Soldier"
            CFrameMissao = CFrame.new(-7906.81, 5634.66, -1411.99)
            CFrameMob = CFrame.new(-7836.75, 5645.66, -1790.62)

        elseif MeuNivel >= 625 and MeuNivel <= 649 then
            Mob = "Pirata Galley"
            NivelMissao = 1
            NomeMissao = "FountainQuest"
            NomeMob = "Galley Pirate"
            CFrameMissao = CFrame.new(5259.81, 37.35, 4050.02)
            CFrameMob = CFrame.new(5551.02, 78.90, 3930.41)

        elseif MeuNivel >= 650 then
            Mob = "Capitão Galley"
            NivelMissao = 2
            NomeMissao = "FountainQuest"
            NomeMob = "Galley Captain"
            CFrameMissao = CFrame.new(5259.81, 37.35, 4050.02)
            CFrameMob = CFrame.new(5441.95, 42.50, 4950.09)
        end
    elseif Mundo2 then

        if MeuNivel >= 700 and MeuNivel <= 724 then
            Mob = "Cyborg Marinho"
            NivelMissao = 1
            NomeMissao = "Area1Quest"
            NomeMob = "Raider"
            CFrameMissao = CFrame.new(-425.50, 73.00, 1837.09)
            CFrameMob = CFrame.new(-746.55, 39.00, 2390.60)

        elseif MeuNivel >= 725 and MeuNivel <= 774 then
            Mob = "Mercenário"
            NivelMissao = 2
            NomeMissao = "Area1Quest"
            NomeMob = "Mercenary"
            CFrameMissao = CFrame.new(-425.50, 73.00, 1837.09)
            CFrameMob = CFrame.new(-958.29, 61.44, 1410.62)

        elseif MeuNivel >= 775 and MeuNivel <= 799 then
            Mob = "Guarda do Guarda-Costas"
            NivelMissao = 1
            NomeMissao = "Area2Quest"
            NomeMob = "Swan Pirate"
            CFrameMissao = CFrame.new(635.27, 73.12, 918.66)
            CFrameMob = CFrame.new(727.20, 73.11, 1055.38)

        elseif MeuNivel >= 800 and MeuNivel <= 874 then
            Mob = "Guarda-Costas"
            NivelMissao = 2
            NomeMissao = "Area2Quest"
            NomeMob = "Factory Staff"
            CFrameMissao = CFrame.new(635.27, 73.12, 918.66)
            CFrameMob = CFrame.new(295.41, 73.12, -56.18)

        elseif MeuNivel >= 875 and MeuNivel <= 899 then
            Mob = "Marinha de Gelo"
            NivelMissao = 1
            NomeMissao = "MarineQuest3"
            NomeMob = "Marine Lieutenant"
            CFrameMissao = CFrame.new(-2440.40, 73.00, -3215.83)
            CFrameMob = CFrame.new(-2713.20, 73.00, -3135.72)

        elseif MeuNivel >= 900 and MeuNivel <= 949 then
            Mob = "Capitão dos Gelos"
            NivelMissao = 2
            NomeMissao = "MarineQuest3"
            NomeMob = "Marine Captain"
            CFrameMissao = CFrame.new(-2440.40, 73.00, -3215.83)
            CFrameMob = CFrame.new(-1821.56, 73.00, -3235.12)

        elseif MeuNivel >= 950 and MeuNivel <= 974 then
            Mob = "Yeti da Neve"
            NivelMissao = 1
            NomeMissao = "SnowMountainQuest"
            NomeMob = "Snow Lurker"
            CFrameMissao = CFrame.new(605.60, 400.03, -5372.48)
            CFrameMob = CFrame.new(697.10, 408.90, -5620.46)

        elseif MeuNivel >= 975 and MeuNivel <= 999 then
            Mob = "Assassino da Neve"
            NivelMissao = 2
            NomeMissao = "SnowMountainQuest"
            NomeMob = "Snow Soldier"
            CFrameMissao = CFrame.new(605.60, 400.03, -5372.48)
            CFrameMob = CFrame.new(522.61, 425.00, -5639.26)

        elseif MeuNivel >= 1000 and MeuNivel <= 1049 then
            Mob = "Golem de Lava"
            NivelMissao = 1
            NomeMissao = "FireSideQuest"
            NomeMob = "Magma Ninja"
            CFrameMissao = CFrame.new(-5430.31, 15.61, -5292.93)
            CFrameMob = CFrame.new(-5582.05, 14.82, -5998.46)

        elseif MeuNivel >= 1050 and MeuNivel <= 1099 then
            Mob = "Ninja das Chamas"
            NivelMissao = 2
            NomeMissao = "FireSideQuest"
            NomeMob = "Lava Pirate"
            CFrameMissao = CFrame.new(-5430.31, 15.61, -5292.93)
            CFrameMob = CFrame.new(-5198.18, 51.06, -4753.78)

        elseif MeuNivel >= 1100 and MeuNivel <= 1124 then
            Mob = "Peregrino"
            NivelMissao = 1
            NomeMissao = "ShipQuest1"
            NomeMob = "Ship Deckhand"
            CFrameMissao = CFrame.new(1037.93, 125.27, 32971.70)
            CFrameMob = CFrame.new(1187.84, 130.37, 33030.76)

        elseif MeuNivel >= 1125 and MeuNivel <= 1174 then
            Mob = "Marinheiro Fantasma"
            NivelMissao = 2
            NomeMissao = "ShipQuest1"
            NomeMob = "Ship Engineer"
            CFrameMissao = CFrame.new(1037.93, 125.27, 32971.70)
            CFrameMob = CFrame.new(920.46, 125.27, 32786.49)

        elseif MeuNivel >= 1175 and MeuNivel <= 1199 then
            Mob = "Capanga Zumbi"
            NivelMissao = 1
            NomeMissao = "ShipQuest2"
            NomeMob = "Ship Steward"
            CFrameMissao = CFrame.new(969.62, 125.52, 33039.38)
            CFrameMob = CFrame.new(915.42, 125.52, 32976.27)

        elseif MeuNivel >= 1200 and MeuNivel <= 1249 then
            Mob = "Guarda Maldito"
            NivelMissao = 2
            NomeMissao = "ShipQuest2"
            NomeMob = "Ship Officer"
            CFrameMissao = CFrame.new(969.62, 125.52, 33039.38)
            CFrameMob = CFrame.new(890.22, 125.46, 33204.27)

        elseif MeuNivel >= 1250 and MeuNivel <= 1274 then
            Mob = "Bandido da Selva"
            NivelMissao = 1
            NomeMissao = "FrostQuest"
            NomeMob = "Snow Demon"
            CFrameMissao = CFrame.new(5564.97, 28.41, -6236.25)
            CFrameMob = CFrame.new(5702.24, 28.40, -6124.90)

        elseif MeuNivel >= 1275 and MeuNivel <= 1299 then
            Mob = "Assassino da Neve"
            NivelMissao = 2
            NomeMissao = "FrostQuest"
            NomeMob = "Winter Warrior"
            CFrameMissao = CFrame.new(5564.97, 28.41, -6236.25)
            CFrameMob = CFrame.new(5380.20, 42.10, -6465.80)

        elseif MeuNivel >= 1300 and MeuNivel <= 1324 then
            Mob = "Criatura das Sombras"
            NivelMissao = 1
            NomeMissao = "ForgottenQuest"
            NomeMob = "Sea Soldier"
            CFrameMissao = CFrame.new(-3050.44, 238.67, -10020.83)
            CFrameMob = CFrame.new(-3006.75, 238.67, -10249.42)

        elseif MeuNivel >= 1325 and MeuNivel <= 1349 then
            Mob = "Soldado dos Mares"
            NivelMissao = 2
            NomeMissao = "ForgottenQuest"
            NomeMob = "Water Fighter"
            CFrameMissao = CFrame.new(-3050.44, 238.67, -10020.83)
            CFrameMob = CFrame.new(-3471.24, 240.22, -10573.37)

        elseif MeuNivel >= 1350 and MeuNivel <= 1374 then
            Mob = "Tubarão Lutador"
            NivelMissao = 1
            NomeMissao = "SharkQuest1"
            NomeMob = "Shark Warrior"
            CFrameMissao = CFrame.new(-3220.55, 300.40, -28695.10)
            CFrameMob = CFrame.new(-3200.47, 300.16, -28950.50)

        elseif MeuNivel >= 1375 and MeuNivel <= 1424 then
            Mob = "Assassino do Tubarão"
            NivelMissao = 2
            NomeMissao = "SharkQuest1"
            NomeMob = "Shark Master"
            CFrameMissao = CFrame.new(-3220.55, 300.40, -28695.10)
            CFrameMob = CFrame.new(-3050.20, 330.00, -29145.18)

        elseif MeuNivel >= 1425 and MeuNivel <= 1449 then
            Mob = "Mestre das Marés"
            NivelMissao = 1
            NomeMissao = "SharkQuest2"
            NomeMob = "Marine Commodore"
            CFrameMissao = CFrame.new(-3220.55, 300.40, -28695.10)
            CFrameMob = CFrame.new(-3450.34, 330.50, -29250.74)

        elseif MeuNivel >= 1450 then
            Mob = "Comandante das Marés"
            NivelMissao = 2
            NomeMissao = "SharkQuest2"
            NomeMob = "Marine Rear Admiral"
            CFrameMissao = CFrame.new(-3220.55, 300.40, -28695.10)
            CFrameMob = CFrame.new(-3600.23, 338.90, -29450.33)
        end
    elseif Mundo3 then

        if MeuNivel >= 1500 and MeuNivel <= 1524 then
            Mob = "Milionário Pirata"
            NivelMissao = 1
            NomeMissao = "PiratePortQuest"
            NomeMob = "Pirate Millionaire"
            CFrameMissao = CFrame.new(-290.07, 42.90, 5581.58)
            CFrameMob = CFrame.new(-245.99, 47.30, 5584.10)

        elseif MeuNivel >= 1525 and MeuNivel <= 1574 then
            Mob = "Bilionário Pistoleiro"
            NivelMissao = 2
            NomeMissao = "PiratePortQuest"
            NomeMob = "Pistol Billionaire"
            CFrameMissao = CFrame.new(-290.07, 42.90, 5581.58)
            CFrameMob = CFrame.new(-187.33, 86.23, 6013.51)

        elseif MeuNivel >= 1575 and MeuNivel <= 1599 then
            Mob = "Guerreiro da Tripulação do Dragão"
            NivelMissao = 1
            NomeMissao = "AmazonQuest"
            NomeMob = "Dragon Crew Warrior"
            CFrameMissao = CFrame.new(5832.83, 51.68, -1101.51)
            CFrameMob = CFrame.new(6141.14, 51.35, -1340.73)

        elseif MeuNivel >= 1600 and MeuNivel <= 1624 then 
            Mob = "Arqueiro da Tripulação do Dragão"
            NomeMissao = "AmazonQuest"
            NivelMissao = 2
            NomeMob = "Dragon Crew Archer"
            CFrameMissao = CFrame.new(5833.11, 51.60, -1103.06)
            CFrameMob = CFrame.new(6616.41, 441.76, 446.04)

        elseif MeuNivel >= 1625 and MeuNivel <= 1649 then
            Mob = "Ilhéusa"
            NomeMissao = "AmazonQuest2"
            NivelMissao = 1
            NomeMob = "Female Islander"
            CFrameMissao = CFrame.new(5446.87, 601.62, 749.45)
            CFrameMob = CFrame.new(4685.25, 735.80, 815.34)

        elseif MeuNivel >= 1650 and MeuNivel <= 1699 then 
            Mob = "Gigante Ilhéu"
            NomeMissao = "AmazonQuest2"
            NivelMissao = 2
            NomeMob = "Giant Islander"
            CFrameMissao = CFrame.new(5446.87, 601.62, 749.45)
            CFrameMob = CFrame.new(4729.09, 590.43, -36.97)

        elseif MeuNivel >= 1700 and MeuNivel <= 1724 then
            Mob = "Comodoro da Marinha"
            NivelMissao = 1
            NomeMissao = "MarineTreeIsland"
            NomeMob = "Marine Commodore"
            CFrameMissao = CFrame.new(2180.54, 27.81, -6741.54)
            CFrameMob = CFrame.new(2286.00, 73.13, -7159.80)

        elseif MeuNivel >= 1725 and MeuNivel <= 1774 then
            Mob = "Vice-Almirante da Marinha"
            NomeMob = "Marine Rear Admiral"
            NomeMissao = "MarineTreeIsland"
            NivelMissao = 2
            CFrameMissao = CFrame.new(2179.98, 28.73, -6740.05)
            CFrameMob = CFrame.new(3656.77, 160.52, -7001.59)

        elseif MeuNivel >= 1775 and MeuNivel <= 1799 then
            Mob = "Saqueador Tritão"
            NivelMissao = 1
            NomeMissao = "DeepForestIsland3"
            NomeMob = "Fishman Raider"
            CFrameMissao = CFrame.new(-10581.65, 330.87, -8761.18)
            CFrameMob = CFrame.new(-10407.52, 331.76, -8368.51)

        elseif MeuNivel >= 1800 and MeuNivel <= 1824 then
            Mob = "Capitão Tritão"
            NivelMissao = 2
            NomeMissao = "DeepForestIsland3"
            NomeMob = "Fishman Captain"
            CFrameMissao = CFrame.new(-10581.65, 330.87, -8761.18)
            CFrameMob = CFrame.new(-10994.70, 352.38, -9002.11)

        elseif MeuNivel >= 1825 and MeuNivel <= 1849 then
            Mob = "Pirata da Floresta"
            NivelMissao = 1
            NomeMissao = "DeepForestIsland"
            NomeMob = "Forest Pirate"
            CFrameMissao = CFrame.new(-13234.04, 331.48, -7625.40)
            CFrameMob = CFrame.new(-13274.47, 332.37, -7769.58)

        elseif MeuNivel >= 1850 and MeuNivel <= 1899 then
            Mob = "Pirata Mitológico"
            NivelMissao = 2
            NomeMissao = "DeepForestIsland"
            NomeMob = "Mythological Pirate"
            CFrameMissao = CFrame.new(-13234.04, 331.48, -7625.40)
            CFrameMob = CFrame.new(-13680.60, 501.08, -6991.18)

        elseif MeuNivel >= 1900 and MeuNivel <= 1924 then
            Mob = "Pirata da Selva"
            NivelMissao = 1
            NomeMissao = "DeepForestIsland2"
            NomeMob = "Jungle Pirate"
            CFrameMissao = CFrame.new(-12680.38, 389.97, -9902.01)
            CFrameMob = CFrame.new(-12256.16, 331.73, -10485.83)

        elseif MeuNivel >= 1925 and MeuNivel <= 1974 then
            Mob = "Musketeer Pirata"
            NivelMissao = 2
            NomeMissao = "DeepForestIsland2"
            NomeMob = "Musketeer Pirate"
            CFrameMissao = CFrame.new(-12680.38, 389.97, -9902.01)
            CFrameMob = CFrame.new(-13457.90, 391.54, -9859.17)

        elseif MeuNivel >= 1975 and MeuNivel <= 1999 then
            Mob = "Esqueleto Reencarnado"
            NivelMissao = 1
            NomeMissao = "HauntedQuest1"
            NomeMob = "Reborn Skeleton"
            CFrameMissao = CFrame.new(-9479.21, 141.21, 5566.09)
            CFrameMob = CFrame.new(-8763.72, 165.72, 6159.86)

        elseif MeuNivel >= 2000 and MeuNivel <= 2024 then
            Mob = "Zumbi Vivo"
            NivelMissao = 2
            NomeMissao = "HauntedQuest1"
            NomeMob = "Living Zombie"
            CFrameMissao = CFrame.new(-9479.21, 141.21, 5566.09)
            CFrameMob = CFrame.new(-10144.13, 138.62, 5838.08)

        elseif MeuNivel >= 2025 and MeuNivel <= 2049 then
            Mob = "Alma Demoníaca"
            NivelMissao = 1
            NomeMissao = "HauntedQuest2"
            NomeMob = "Demonic Soul"
            CFrameMissao = CFrame.new(-9516.99, 172.01, 6078.46)
            CFrameMob = CFrame.new(-9505.87, 172.10, 6158.99)

        elseif MeuNivel >= 2050 and MeuNivel <= 2074 then
            Mob = "Múmia Possuída"
            NivelMissao = 2
            NomeMissao = "HauntedQuest2"
            NomeMob = "Posessed Mummy"
            CFrameMissao = CFrame.new(-9516.99, 172.01, 6078.46)
            CFrameMob = CFrame.new(-9582.02, 6.25, 6205.47)

        elseif MeuNivel >= 2075 and MeuNivel <= 2099 then
            Mob = "Batedor Amendoim"
            NivelMissao = 1
            NomeMissao = "NutsIslandQuest"
            NomeMob = "Peanut Scout"
            CFrameMissao = CFrame.new(-2104.39, 38.10, -10194.21)
            CFrameMob = CFrame.new(-2143.24, 47.72, -10029.99)

        elseif MeuNivel >= 2100 and MeuNivel <= 2124 then
            Mob = "Presidente Amendoim"
            NivelMissao = 2
            NomeMissao = "NutsIslandQuest"
            NomeMob = "Peanut President"
            CFrameMissao = CFrame.new(-2104.39, 38.10, -10194.21)
            CFrameMob = CFrame.new(-1859.35, 38.10, -10422.42)

        elseif MeuNivel >= 2125 and MeuNivel <= 2149 then
            Mob = "Chef de Sorvete"
            NivelMissao = 1
            NomeMissao = "IceCreamIslandQuest"
            NomeMob = "Ice Cream Chef"
            CFrameMissao = CFrame.new(-820.64, 65.81, -10965.79)
            CFrameMob = CFrame.new(-872.24, 65.81, -10919.95)

        elseif MeuNivel >= 2150 and MeuNivel <= 2199 then
            Mob = "Comandante de Sorvete"
            NivelMissao = 2
            NomeMissao = "IceCreamIslandQuest"
            NomeMob = "Ice Cream Commander"
            CFrameMissao = CFrame.new(-820.64, 65.81, -10965.79)
            CFrameMob = CFrame.new(-558.06, 112.04, -11290.77)

        elseif MeuNivel >= 2200 and MeuNivel <= 2224 then
            Mob = "Criador de Biscoitos"
            NivelMissao = 1
            NomeMissao = "CakeQuest1"
            NomeMob = "Cookie Crafter"
            CFrameMissao = CFrame.new(-2021.32, 37.79, -12028.72)
            CFrameMob = CFrame.new(-2374.13, 37.79, -12125.30)

        elseif MeuNivel >= 2225 and MeuNivel <= 2249 then
            Mob = "Guardião do Bolo"
            NivelMissao = 2
            NomeMissao = "CakeQuest1"
            NomeMob = "Cake Guard"
            CFrameMissao = CFrame.new(-2021.32, 37.79, -12028.72)
            CFrameMob = CFrame.new(-1598.30, 43.77, -12244.58)

        elseif MeuNivel >= 2250 and MeuNivel <= 2274 then
            Mob = "Equipe de Confeitaria"
            NivelMissao = 1
            NomeMissao = "CakeQuest2"
            NomeMob = "Baking Staff"
            CFrameMissao = CFrame.new(-1927.91, 37.79, -12842.53)
            CFrameMob = CFrame.new(-1887.80, 77.61, -12998.35)

        elseif MeuNivel >= 2275 and MeuNivel <= 2299 then
            Mob = "Chef Principal"
            NivelMissao = 2
            NomeMissao = "CakeQuest2"
            NomeMob = "Head Baker"
            CFrameMissao = CFrame.new(-1927.91, 37.79, -12842.53)
            CFrameMob = CFrame.new(-2216.18, 82.88, -12869.29)

        elseif MeuNivel >= 2300 and MeuNivel <= 2324 then
            Mob = "Guerreiro do Cacau"
            NivelMissao = 1
            NomeMissao = "ChocQuest1"
            NomeMob = "Cocoa Warrior"
            CFrameMissao = CFrame.new(233.22, 29.87, -12201.23)
            CFrameMob = CFrame.new(-21.55, 80.57, -12352.38)

        elseif MeuNivel >= 2325 and MeuNivel <= 2349 then
            Mob = "Lutador Barra de Chocolate"
            NivelMissao = 2
            NomeMissao = "ChocQuest1"
            NomeMob = "Chocolate Bar Battler"
            CFrameMissao = CFrame.new(233.22, 29.87, -12201.23)
            CFrameMob = CFrame.new(582.59, 77.18, -12463.16)

        elseif MeuNivel >= 2350 and MeuNivel <= 2374 then
            Mob = "Ladrão Doce"
            NivelMissao = 1
            NomeMissao = "ChocQuest2"
            NomeMob = "Sweet Thief"
            CFrameMissao = CFrame.new(150.50, 30.69, -12774.50)
            CFrameMob = CFrame.new(165.18, 76.05, -12600.83)

        elseif MeuNivel >= 2375 and MeuNivel <= 2399 then
            Mob = "Rebelde Doce"
            NivelMissao = 2
            NomeMissao = "ChocQuest2"
            NomeMob = "Candy Rebel"
            CFrameMissao = CFrame.new(150.50, 30.69, -12774.50)
            CFrameMob = CFrame.new(134.86, 77.24, -12876.54)

        elseif MeuNivel >= 2400 and MeuNivel <= 2424 then
            Mob = "Pirata Doce"
            NivelMissao = 1
            NomeMissao = "CandyQuest1"
            NomeMob = "Candy Pirate"
            CFrameMissao = CFrame.new(-1150.04, 20.37, -14446.33)
            CFrameMob = CFrame.new(-1310.50, 26.01, -14562.40)

        elseif MeuNivel >= 2425 and MeuNivel <= 2449 then
            Mob = "Demônio da Neve"
            NivelMissao = 2
            NomeMissao = "CandyQuest1"
            NomeMob = "Snow Demon"
            CFrameMissao = CFrame.new(-1150.04, 20.37, -14446.33)
            CFrameMob = CFrame.new(-880.20, 71.24, -14538.60)

        elseif MeuNivel >= 2450 and MeuNivel <= 2474 then
            Mob = "Fora-da-lei da Ilha"
            NivelMissao = 1
            NomeMissao = "TikiQuest1"
            NomeMob = "Isle Outlaw"
            CFrameMissao = CFrame.new(-16545.93, 55.68, -173.23)
            CFrameMob = CFrame.new(-16120.60, 116.52, -103.03)

        elseif MeuNivel >= 2475 and MeuNivel <= 2499 then
            Mob = "Garoto da Ilha"
            NivelMissao = 2
            NomeMissao = "TikiQuest1"
            NomeMob = "Island Boy"
            CFrameMissao = CFrame.new(-16545.93, 55.68, -173.23)
            CFrameMob = CFrame.new(-16751.31, 121.22, -264.01)

        elseif MeuNivel >= 2500 and MeuNivel <= 2524 then
            Mob = "Guerreiro Bronzeado"
            NivelMissao = 1
            NomeMissao = "TikiQuest2"
            NomeMob = "Sun-kissed Warrio"
            CFrameMissao = CFrame.new(-16539.07, 55.68, 1051.57)
            CFrameMob = CFrame.new(-16294.67, 32.78, 1062.48)

        elseif MeuNivel >= 2525 then
            Mob = "Campeão da Ilha"
            NivelMissao = 2
            NomeMissao = "TikiQuest2"
            NomeMob = "Isle Champion"
            CFrameMissao = CFrame.new(-16539.07, 55.68, 1051.57)
            CFrameMob = CFrame.new(-16933.21, 93.35, 999.45)
        end
    end
end

function ehNulo(objeto)
    return (objeto == nil)
end
function arredondar(numero)
    return math.floor(numero + 0.5)
end
function AtualizarESPDasIlhas()
    pcall(function()
        for i,v in pairs(game:GetService("Workspace").Map:GetChildren()) do
            if v:IsA("Model") or v:IsA("Folder") then
                if not ILHAS[v.Name] then
                    ILHAS[v.Name] = true
                    
                    local marcador = Instance.new("BillboardGui")
                    marcador.Name = "ESP_ILHA"
                    marcador.Parent = v:FindFirstChildWhichIsA("BasePart") or v:FindFirstChildWhichIsA("Part")
                    marcador.Adornee = marcador.Parent
                    marcador.AlwaysOnTop = true
                    marcador.Size = UDim2.new(0, 150, 0, 50)

                    local texto = Instance.new("TextLabel")
                    texto.Parent = marcador
                    texto.Size = UDim2.new(1, 0, 1, 0)
                    texto.Text = v.Name
                    texto.TextColor3 = Color3.fromRGB(255, 255, 0)
                    texto.BackgroundTransparency = 1
                    texto.TextScaled = true
                end
            end
        end
    end)
end

function AtualizarESPdeJogadores()
    pcall(function()
        for _, jogador in pairs(game:GetService("Players"):GetPlayers()) do
            if jogador ~= game.Players.LocalPlayer then
                local personagem = jogador.Character
                if personagem and personagem:FindFirstChild("HumanoidRootPart") then
                    
                    if not personagem:FindFirstChild("ESP_JOGADOR") then
                        local esp = Instance.new("BillboardGui")
                        esp.Name = "ESP_JOGADOR"
                        esp.Parent = personagem.HumanoidRootPart
                        esp.Adornee = personagem.HumanoidRootPart
                        esp.AlwaysOnTop = true
                        esp.Size = UDim2.new(0, 200, 0, 50)

                        local nome = Instance.new("TextLabel")
                        nome.Parent = esp
                        nome.Size = UDim2.new(1, 0, 1, 0)
                        nome.BackgroundTransparency = 1
                        nome.Text = jogador.Name
                        nome.TextScaled = true
                        nome.TextColor3 = Color3.fromRGB(0, 255, 0)
                    end
                end
            end
        end
    end)
end

function AtualizarESPdeBaus()
    pcall(function()
        for _, baú in pairs(game:GetService("Workspace"):GetChildren()) do
            if string.find(baú.Name, "Chest") and baú:IsA("Model") then
                
                local base = baú:FindFirstChildWhichIsA("BasePart")
                if base and not base:FindFirstChild("ESP_BAU") then
                    
                    local esp = Instance.new("BillboardGui")
                    esp.Name = "ESP_BAU"
                    esp.Parent = base
                    esp.Adornee = base
                    esp.AlwaysOnTop = true
                    esp.Size = UDim2.new(0, 180, 0, 50)

                    local texto = Instance.new("TextLabel")
                    texto.Parent = esp
                    texto.Size = UDim2.new(1, 0, 1, 0)
                    texto.BackgroundTransparency = 1
                    texto.TextScaled = true
                    texto.TextColor3 = Color3.fromRGB(255, 215, 0)
                    texto.Text = baú.Name
                end
            end
        end
    end)
end

function AtualizarESPdeFrutas()
    pcall(function()
        for _, fruta in pairs(game:GetService("Workspace"):GetChildren()) do
            if fruta:IsA("Tool") and fruta:FindFirstChild("Handle") then
                
                if not fruta.Handle:FindFirstChild("ESP_FRUTA") then
                    
                    local esp = Instance.new("BillboardGui")
                    esp.Name = "ESP_FRUTA"
                    esp.Parent = fruta.Handle
                    esp.Adornee = fruta.Handle
                    esp.AlwaysOnTop = true
                    esp.Size = UDim2.new(0, 160, 0, 45)

                    local texto = Instance.new("TextLabel")
                    texto.Parent = esp
                    texto.Size = UDim2.new(1, 0, 1, 0)
                    texto.BackgroundTransparency = 1
                    texto.TextScaled = true
                    texto.TextColor3 = Color3.fromRGB(255, 0, 0)
                    texto.Text = fruta.Name
                end
            end
        end
    end)
end

function AtualizarESPdasFlores()
    pcall(function()
        for _, flor in pairs(game:GetService("Workspace"):GetChildren()) do
            if flor.Name == "Flower1" or flor.Name == "Flower2" or flor.Name == "BlueFlower" or flor.Name == "RedFlower" or flor.Name == "YellowFlower" then
                
                local parte = flor:FindFirstChildWhichIsA("BasePart") or flor:FindFirstChild("Handle")
                if parte and not parte:FindFirstChild("ESP_FLOR") then
                    
                    local esp = Instance.new("BillboardGui")
                    esp.Name = "ESP_FLOR"
                    esp.Parent = parte
                    esp.Adornee = parte
                    esp.AlwaysOnTop = true
                    esp.Size = UDim2.new(0, 200, 0, 60)

                    local texto = Instance.new("TextLabel")
                    texto.Parent = esp
                    texto.Size = UDim2.new(1, 0, 1, 0)
                    texto.BackgroundTransparency = 1
                    texto.TextScaled = true
                    texto.TextColor3 = Color3.fromRGB(255, 0, 255)
                    texto.Text = "Flor: " .. flor.Name
                end
            end
        end
    end)
end
function AtualizarESPdeFrutasReais()
    pcall(function()
        for _, objeto in pairs(game:GetService("Workspace"):GetChildren()) do
            if objeto:IsA("Tool") and objeto:FindFirstChild("Handle") then
                if not objeto.Handle:FindFirstChild("ESP_FRUTA_REAL") then
                    
                    local esp = Instance.new("BillboardGui")
                    esp.Name = "ESP_FRUTA_REAL"
                    esp.Parent = objeto.Handle
                    esp.Adornee = objeto.Handle
                    esp.AlwaysOnTop = true
                    esp.Size = UDim2.new(0, 180, 0, 60)

                    local texto = Instance.new("TextLabel")
                    texto.Parent = esp
                    texto.Size = UDim2.new(1, 0, 1, 0)
                    texto.BackgroundTransparency = 1
                    texto.TextScaled = true
                    texto.TextColor3 = Color3.fromRGB(0, 255, 255)
                    texto.Text = "Fruta: " .. objeto.Name
                end
            end
        end
    end)
end
function TrocarServidor()
    local codigoRegiao = "en-us"

    local sucesso, lista = pcall(function()
        return game:GetService("HttpService"):JSONDecode(
            game:HttpGet("https://games.roblox.com/v1/games/" .. game.PlaceId ..
                "/servers/Public?sortOrder=Desc&limit=100&region=" .. codigoRegiao)
        )
    end)

    if sucesso then
        for _, servidor in pairs(lista.data) do
            if servidor.playing < servidor.maxPlayers then
                if servidor.id ~= game.JobId then
                    setclipboard(servidor.id)
                    
                    game:GetService("TeleportService"):TeleportToPlaceInstance(
                        game.PlaceId, servidor.id, game.Players.LocalPlayer
                    )
                    
                    wait(3)
                end
            end
        end
    end
end

function VerificarIncursao()
    local raids = game:GetService("ReplicatedStorage").Raids
    return raids:FindFirstChild("Active")
end
