<input type="radio" class="isPC" value="1" name="attr_pc" checked> PC
<input type="radio" class="isNPC" value="0" name="attr_pc"> NPC
<div class="sheet-1colrow" style="text-align:center;">
  <div class="sheet-col">
      <p style="text-align: center;">
            <img src="http://upload.wikimedia.org/wikipedia/en/c/cc/Fire_Emblem_series_logo.png" style="max-height: 100px;" alt="Pathfinder RPG Character Sheet" />
        </p>
	</div>
</div>
<div class="sheet-pc">
	<b>Show Character Details?</b>
	<input type="checkbox" class="sheet-pc-details-show" title="character-details-show" name="attr_character-details-show" value="1" style="opacity:0;width: 16px;height: 16px;position: relative;top: 5px;left: 6px;margin: -10px;cursor: pointer;z-index: 1;" checked/><span></span>
	<div class="sheet-pc-details">
		<div class="sheet-table">  
			<span class="sheet-table-name">Character Details</span> 
		</div>
		<div>
			<div>    
				<span class="sheet-table-data-center" style="width:25%;"><input title="character_name" type="text" name="attr_character_name" placeholder="Character Name"/></span>
				<span class="sheet-table-data-center" style="width:20%;"><input title="player-name" type="text" name="attr_player-name" placeholder="Player Name"/></span>	
				<span class="sheet-table-data-center" style="width:20%;"><input title="class" type="text" name="attr_class" placeholder="Class"/></span>
                <span class="sheet-table-data-center" style="width:30%;"><input title="level" type="text" name="attr_level" placeholder="Level"/></span>
				<span class="sheet-table-data-center" style="width:15%;"><input title="Sex" type="text" name="attr_sex" placeholder="Sex"/></span>
				<span class="sheet-table-data-center" style="width:25%;">
					<select title="Unit Type" name="attr_type">
						<option value="None">Select Unit Type</option>
						<option value="Foot">Foot</option>
                        <option value="Armored">Armored</option>
                        <option value="Dragon">Dragon</option>
                        <option value="Monster">Monster</option>
						<option value="Male Mounted">Male Mounted</option>
						<option value="Female Mounted">Female Mounted</option>
                        <option value="Male Flying">Male Flying</option>
                        <option value="Female Flying">Female Flying</option>
                        <option value="Male Armored/Mounted">Male Armored/Mounted</option>
                        <option value="Female Armored/Mounted">Female Armored/Mounted</option>
                        <option value="Male Dragon/Flying">Male Dragon/Flying</option>
                        <option value="Female Dragon/Flying">Female Dragon/Flying</option>
					</select>
				</span>  
			</div>
			<div>		
				<span class="sheet-table-data-center" style="width:8%;"><input title="height" type="text" name="attr_height" placeholder="Height"/></span>
				<span class="sheet-table-data-center" style="width:8%;"><input title="weight" type="text" name="attr_weight" step="any" placeholder="Weight"/></span>
				<span class="sheet-table-data-center" style="width:25%;"><input title="hair" type="text" name="attr_hair" placeholder="Hair Details"/></span>
				<span class="sheet-table-data-center" style="width:25%;"><input title="eyes" type="text" name="attr_eyes" placeholder="Eye Details"/></span>
				<span class="sheet-table-data-center" style="width:25%;"><input title="skin" type="text" name="attr_skin" placeholder="Skin Details"/></span>
			</div>
			<div>	
				<span class="sheet-table-data-center" style="width:8%;"><input title="age" type="number" name="attr_age" placeholder="Age"/></span>
				<span class="sheet-table-data-center" style="width:30%;"><input title="deity" type="text" name="attr_deity" placeholder="Deity"/></span>
				<span class="sheet-table-data-center" style="width:30%;"><input title="homeland" type="text" name="attr_homeland" placeholder="Homeland"/></span>
				<span class="sheet-table-data-center" style="width:30%;"><input title="occupation" type="text" name="attr_occupation" placeholder="Occupation"/></span>
			</div>
			<div>				
			</div>
		</div>
	</div>
	<br/>
	<b>Show Ability Scores and Class Information?</b>
	<input type="checkbox" class="sheet-pc-abilities-show" title="abilities-show" name="attr_abilities-show" value="1" style="opacity:0;width: 16px;height: 16px;position: relative;top: 5px;left: 6px;margin: -10px;cursor: pointer;z-index: 1;" checked/><span></span>
	<div class="sheet-table sheet-pc-abilities">
		<div class="sheet-table-row">
			<div class="sheet-table-data-center" style="vertical-align:top;">
				<div class="sheet-table">
					<span class="sheet-table-name">Stats</span>
					<div class="sheet-table-row">
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">STR/MAG</span>	<span class="sheet-table-data-center"><input title="STR/MAG" type="number" name="attr_STR/MAG" style="width:10%;"></span>
                    <span class="sheet-table-header">Growth Rate STR/MAG</span> <input title="Growth Rate STR/MAG" type="number" name="attr_GSTR/MAG" style="width:10%;"></span>
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">DEF</span>	<span class="sheet-table-data-center"><input title="DEF" type="number" name="attr_DEF" style="width:10%;"></span>
                    <span class="sheet-table-header">Growth Rate DEF</span> <input title="Growth Rate DEF" type="number" name="attr_GDEF" style="width:10%;"></span>
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">RES</span> <span class="sheet-table-data-center"><input title="RES" type="number" name="attr_RES" style="width:10%;"></span>
					<span class="sheet-table-header">Growth Rate RES</span>	<span class="sheet-table-data-center"><input title="Growth Rate RES" type="number" name="attr_GRE" style="width:10%;"></span>
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">SKL</span>	<span class="sheet-table-data-center"><input title="SKL" type="number" name="attr_SKL" style="width:10%;"></span>
					<span class="sheet-table-header">Growth Rate SKL</span>	<span class="sheet-table-data-center"><input title="Growth Rate SKL" type="number" name="attr_GSKL" style="width:10%;"></span>
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">SPD</span>	<span class="sheet-table-data-center"><input title="SPD" type="number" name="attr_SPD" style="width:10%;"></span>
					<span class="sheet-table-header">Growth Rate SPD</span>	<span class="sheet-table-data-center"><input title="Growth Rate SPD" type="number" name="attr_GSPD" style="width:10%;"></span>
					</div>
					<div class="sheet-table-row">
					<span class="sheet-table-header">LUK</span>	<span class="sheet-table-data-center"><input title="LUK" type="number" name="attr_LUK" style="width:10%;"></span>
					<span class="sheet-table-header">Growth Rate LUK</span>	<span class="sheet-table-data-center"><input title="Growth Rate LUK" type="number" name="attr_GLUK" style="width:10%;"></span>
					</div>
                    <div class="sheet-table-row">
					<span class="sheet-table-header">Move</span> <span class="sheet-table-data-center"><input title="MOV" type="number" name="attr_MOV"></span>
					</div>
                    <div class="sheet-table-row">
                    <span class="sheet-table-header">CON</span> <span class="sheet-table-data-center"><input title="CON" type="number" name="attr_CON"></span>
					</div>
                    <div class="sheet-table-row">
                    <span class="sheet-table-header">AID</span> <span class="sheet-table-data-center"><input title="AID" type="number" name="attr_AID"></span>
					</div>
				</div>
			</div>
			<div class="sheet-table-data-center">
			&nbsp;
			</div>
			<div class="sheet-table-data-center">
				<div class="sheet-table">
					<span class="sheet-table-name">Class Information</span>
					<div class="sheet-table-row">
						<span class="sheet-table-header">HP</span>
					</div>
					<div class="sheet-table-row">
						<span class="sheet-table-data-center" style="width:10%;"><input title="HP" type="number" name="attr_HP" value="0"></span>
					</div>
				</div>
			</div>
		</div>
	</div>
	<br>
			<div class="sheet-table-data-center">
			&nbsp;
			</div>
			<div class="sheet-table-data-center" style="width:60%;vertical-align:top;">
				<div class="sheet-table">
					<span class="sheet-table-name">Currency and Experience</span>
					<div class="sheet-table-row">
						<span class="sheet-table-row-name">Gold</span>
						<span class="sheet-table-data-center"><input title="Gold" type="number" name="attr_Gold" value="0" style="width:90%;"></span>
					</div>
				</div>
				<div class="sheet-table">
					<div class="sheet-table-row">
  					<span class="sheet-table-data-center"><input title="experience" type="text" name="attr_experience" placeholder="Current exp"></span>
						<span class="sheet-table-data-center" style="vertical-align:middle;font-size:150%;"><b>/</b></span>
						<span class="sheet-table-data-center"><input title="experience|max" type="text" name="attr_experience_max" placeholder="Exp to next level"></span>
					</div>
				</div>
			</div>
		</div>
	</div>
	<br>
	<b>Skills</b>
<td colspan="2"><label>Skill 1:</label><input type="text" name="attr_Skill1"/></td> 
<td colspan="2"><label>Skill 2:</label><input type="text" name="attr_Skill2"/></td> 
<td colspan="2"><label>Skill 3:</label><input type="text" name="attr_Skill3"/></td> 
<td colspan="2"><label>Skill 4:</label><input type="text" name="attr_Skill4"/></td> 
<td colspan="2"><label>Skill 5:</label><input type="text" name="attr_Skill5"/></td>
<td colspan="2"><label>Class Skill 1:</label><input type="text" name="attr_CSkill1"/></td>
<td colspan="2"><label>Class Skill 2:</label><input type="text" name="attr_CSkill2"/></td>
	<br>
	<div class="sheet-pc-weapons">
		<div class="sheet-table">
			<span class="sheet-table-name">Weapons</span>
            <fieldset class="repeating_weapon">  
    			<div class="sheet-table">
					<div class="sheet-table-row1">
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_wname" title="Weapon's Name" placeholder="Name">Name</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_whit" title="Weapon's Hit" placeholder="Attack Modifiers">Hit</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_wadamagedie" title="Damage Dice">Damage Dice</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_wdamage" title="Damage Multiplpier (STR or MAG/2)" placeholder="Damage Modifiers">Damage Modifier</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_wcrit-target" title="Chance of Critical Hit">Crit Chance</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="number" name="attr_wcrit-multiplier" title="Critical Damage Multiplier" min="2">Multiplier</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_wrange" title="Weapon Range">Range</span><br>
                        <span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="number" name="attr_wuses" title="Weapon Uses" value="1" min="1">Uses</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="number" name="attr_wweight" title="Weapon Weight" value="1" step="any" min="1">Weight</span><br>
						<span class="sheet-table-data sheet-left sheet-small-label" style="width:15%;"><input type="text" name="attr_notes" title="Attack Notes" placeholder="Attack Notes">Notes</span><br><br>
					</div>
				</div>		
			</fieldset>
		</div>
	</div>
	<br>
	<div class="sheet-pc-inventory">
		<div class="sheet-table">
			<span class="sheet-table-name">Inventory</span>
            <fieldset class="repeating_item">
			<div class="sheet-table-row">
				<span class="sheet-table-header" style="width:40%;">Name</span><input title="repeating_item_X_name" type="text" name="attr_iname"></span><br>
				<span class="sheet-table-header" style="width:5%;">Qty/Uses</span><input title="repeating_item_X_qty" type="number" name="attr_iqty" value="0"><br>
				<span class="sheet-table-header" style="width:50%;">Description</span><input title="repeating_item_X_description" type="text" name="attr_idescription"><br><br>
			</div>
            </fieldset>
		</div>
	</div>
	<br>
     <td><label>Weapon Proficiency Sword:</label><select name="attr_WPS">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Lance:</label><select name="attr_WPL">
         <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Axe:</label><select name="attr_WPA">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Bow:</label><select name="attr_WPB">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Anima:</label><select name="attr_WPAn">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Light:</label><select name="attr_WPLi">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Dark:</label><select name="attr_WPD">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
 <td><label>Weapon Proficiency Staff:</label><select name="attr_WPSt">
            <option value="-">-</option>
            <option value="E">E</option>
            <option value="D">D</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
<td colspan="2"><label>Support 1:</label><input type="text" name="attr_S1"/></td>
 <td><label>Level:</label><select name="attr_S1Level">
            <option value="-">-</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
<td colspan="2"><label>Support 2:</label><input type="text" name="attr_S2"/></td>
 <td><label>Level:</label><select name="attr_S2Level">
            <option value="-">-</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
<td colspan="2"><label>Support 3:</label><input type="text" name="attr_S3"/></td>
 <td><label>Level:</label><select name="attr_S3Level">
            <option value="-">-</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
<td colspan="2"><label>Support 4:</label><input type="text" name="attr_S4"/></td>
 <td><label>Level:</label><select name="attr_S4Level">
            <option value="-">-</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
<td colspan="2"><label>Support 5:</label><input type="text" name="attr_S5"/></td>
 <td><label>Level:</label><select name="attr_S5Level">
            <option value="-">-</option>
            <option value="C">C</option>
            <option value="B">B</option>
            <option value="A">A</option>
            <option value="S">S</option>
        </select></td>
</rolltemplate>
