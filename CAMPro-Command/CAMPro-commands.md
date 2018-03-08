#Line Mode Command


* [Overview](#overview)
* All Commands
    * [add_arc](#add_arc)
    * [add_line](#add_line)
    * [add_pad](#add_pad)
    * [add_polyline_crv](#add_polyline_crv)
    * [add_polyline_end](#add_polyline_end)
    * [add_polyline_strt](#add_polyline_strt)
    * [add_polyline_xy](#add_polyline_xy)
    * [add_slot](#add_slot)
    * [add_surf_end](#add_surf_end)
    * [add_surf_hole_end](#add_surf_hole_end)
    * [add_surf_hole_strt](#add_surf_hole_strt)
    * [add_surf_poly_crv](#add_surf_poly_crv)
    * [add_surf_poly_end](#add_surf_poly_end)
    * [add_surf_poly_seg](#add_surf_poly_seg)
    * [add_surf_poly_strt](#add_surf_poly_strt)
    * [add_surf_strt](#add_surf_strt)
    * [add_text](#add_text)
    * [affected_filter](#affected_filter)
    * [affected_layer](#affected_layer)
    * [autopanel_ezplan](#autopanel_ezplan)
    * [autopanel_fpc](#autopanel_fpc)
    * [autopanel_fpc_popup](#autopanel_fpc_popup)
    * [autopanel_fpc_seterf](#autopanel_fpc_seterf)
    * [autopanel_fpc_setparameter](#autopanel_fpc_setparameter)
    * [break_feat](#break_feat)
    * [cadnet_reduce_points_to_center](#cadnet_reduce_points_to_center)
    * [chain_add](#chain_add)
    * [chain_add_pilot](#chain_add_pilot)
    * [chain_append](#chain_append)
    * [chain_change](#chain_change)
    * [chain_change_dir](#chain_change_dir)
    * [chain_change_num](#chain_change_num)
    * [chain_del_pilot](#chain_del_pilot)
    * [chain_insert](#chain_insert)
    * [chain_list_add](#chain_list_add)
    * [chain_list_reset](#chain_list_reset)
    * [chain_merge](#chain_merge)
    * [chain_pocket](#chain_pocket)
    * [chain_set_plunge](#chain_set_plunge)
    * [chain_split](#chain_split)
    * [change_edge](#change_edge)
    * [change_step_dependency](#change_step_dependency)
    * [check_inout](#check_inout)
    * [chklist_cdel](#chklist_cdel)
    * [chklist_close](#chklist_close)
    * [chklist_create](#chklist_create)
    * [chklist_cupd](#chklist_cupd)
    * [chklist_erf](#chklist_erf)
    * [chklist_from_lib](#chklist_from_lib)
    * [chklist_hist_close](#chklist_hist_close)
    * [chklist_hist_show](#chklist_hist_show)
    * [chklist_pclear](#chklist_pclear)
    * [chklist_pcopy](#chklist_pcopy)
    * [chklist_ppaste](#chklist_ppaste)
    * [chklist_res_close](#chklist_res_close)
    * [chklist_res_exp](#chklist_res_exp)
    * [chklist_res_show](#chklist_res_show)
    * [chklist_run](#chklist_run)
    * [chklist_show](#chklist_show)
    * [chklist_single](#chklist_single)
    * [chklist_to_layer](#chklist_to_layer)
    * [clear_highlight](#clear_highlight)
    * [clear_layers](#clear_layers)
    * [clip_area_end](#clip_area_end)
    * [clip_area_strt](#clip_area_strt)
    * [clip_area_xy](#clip_area_xy)
    * [clipb_open_job](#clipb_open_job)
    * [close_flow](#close_flow)
    * [close_form](#close_form)
    * [close_job](#close_job)
    * [colors_change](#colors_change)
    * [colors_restore](#colors_restore)
    * [colors_set](#colors_set)
    * [colors_store](#colors_store)
    * [compare_layers](#compare_layers)
    * [compensate_layer](#compensate_layer)
    * [copper_area](#copper_area)
    * [copy_entity](#copy_entity)
    * [copy_feat](#copy_feat)
    * [copy_form](#copy_form)
    * [copy_layer](#copy_layer)
    * [create_entity](#create_entity)
    * [create_layer](#create_layer)
    * [cre_drills_map](#cre_drills_map)
    * [cur_atr_reset](#cur_atr_reset)
    * [cur_atr_set](#cur_atr_set)
    * [datum](#datum)
    * [db_create](#db_create)
    * [db_del](#db_del)
    * [delete_entity](#delete_entity)
    * [delete_feat](#delete_feat)
    * [delete_layer](#delete_layer)
    * [delete_user_file](#delete_user_file)
    * [display_chain](#display_chain)
    * [display_datum](#display_datum)
    * [display_grid](#display_grid)
    * [display_layer](#display_layer)
    * [display_profile](#display_profile)
    * [display_sr](#display_sr)
    * [display_width](#display_width)
    * [disp_off](#disp_off)
    * [disp_on](#disp_on)
    * [disp_snapshot](#disp_snapshot)
    * [duplicate_entity](#duplicate_entity)
    * [editor_group](#editor_group)
    * [editor_page_close](#editor_page_close)
    * [export_job](#export_job)
    * [exposed_area](#exposed_area)
    * [ezcam_get_uid](#ezcam_get_uid)
    * [ezcam_semiauto_dimension_show](#ezcam_semiauto_dimension_show)
    * [ezcam_test_assert](#ezcam_test_assert)
    * [ezcam_test_end](#ezcam_test_end)
    * [ezcam_test_fail](#ezcam_test_fail)
    * [ezcam_test_msg](#ezcam_test_msg)
    * [ezcam_test_start](#ezcam_test_start)
    * [feat_hist_close](#feat_hist_close)
    * [feat_hist_open](#feat_hist_open)
    * [fill_params](#fill_params)
    * [filter_area_end](#filter_area_end)
    * [filter_area_strt](#filter_area_strt)
    * [filter_area_xy](#filter_area_xy)
    * [filter_atr_reset](#filter_atr_reset)
    * [filter_atr_set](#filter_atr_set)
    * [filter_highlight](#filter_highlight)
    * [filter_reset](#filter_reset)
    * [filter_set](#filter_set)
    * [flatten_layer](#flatten_layer)
    * [flip_step](#flip_step)
    * [form_elem_visibility](#form_elem_visibility)
    * [get_affect_layer](#get_affect_layer)
	* [get_disp_layers](#get_disp_layers)
    * [get_select_count](#get_select_count)
    * [get_units](#get_units)
    * [get_user_name](#get_user_name)
    * [get_version](#get_version)
    * [get_work_layer](#get_work_layer)
    * [import_job](#import_job)
    * [info](#info)
    * [input_auto](#input_auto)
    * [input_copy](#input_copy)
    * [input_cur_report](#input_cur_report)
    * [input_dcodes_add](#input_dcodes_add)
    * [input_dcodes_get](#input_dcodes_get)
    * [input_dcodes_match](#input_dcodes_match)
    * [input_dcodes_reset](#input_dcodes_reset)
    * [input_extract_hdr](#input_extract_hdr)
    * [input_hide_page](#input_hide_page)
    * [input_identify](#input_identify)
    * [input_manual](#input_manual)
    * [input_manual_reset](#input_manual_reset)
    * [input_manual_set](#input_manual_set)
    * [input_set_params](#input_set_params)
    * [input_show_page](#input_show_page)
    * [invert_feat](#invert_feat)
    * [matrix_add_col](#matrix_add_col)
    * [matrix_add_layer](#matrix_add_layer)
    * [matrix_add_row](#matrix_add_row)
    * [matrix_add_step](#matrix_add_step)
    * [matrix_auto_rows](#matrix_auto_rows)
    * [matrix_copy_col](#matrix_copy_col)
    * [matrix_copy_row](#matrix_copy_row)
    * [matrix_delete_col](#matrix_delete_col)
    * [matrix_delete_row](#matrix_delete_row)
    * [matrix_dup_col](#matrix_dup_col)
    * [matrix_dup_row](#matrix_dup_row)
    * [matrix_insert_col](#matrix_insert_col)
    * [matrix_insert_row](#matrix_insert_row)
    * [matrix_layer_context](#matrix_layer_context)
    * [matrix_layer_drill](#matrix_layer_drill)
    * [matrix_layer_polar](#matrix_layer_polar)
    * [matrix_layer_type](#matrix_layer_type)
    * [matrix_move_col](#matrix_move_col)
    * [matrix_move_row](#matrix_move_row)
    * [matrix_page_close](#matrix_page_close)
    * [matrix_refresh](#matrix_refresh)
    * [matrix_rename_layer](#matrix_rename_layer)
    * [matrix_rename_step](#matrix_rename_step)
    * [mirror_feat](#mirror_feat)
    * [move_corner](#move_corner)
    * [move_feat](#move_feat)
    * [move_hole](#move_hole)
    * [move_job](#move_job)
    * [move_junction](#move_junction)
    * [move_triplet](#move_triplet)
    * [move_triplets](#move_triplets)
    * [ncd_cre_drill](#ncd_cre_drill)
    * [ncd_ncf_export](#ncd_ncf_export)
    * [ncd_register](#ncd_register)
    * [ncd_set_machine](#ncd_set_machine)
    * [ncd_table_set](#ncd_table_set)
    * [ncset_cur](#ncset_cur)
    * [ncset_units](#ncset_units)
    * [netlist2layer](#netlist2layer)
    * [netlist_auto_reg](#netlist_auto_reg)
    * [netlist_compare](#netlist_compare)
    * [netlist_control](#netlist_control)
    * [netlist_cur2ref_compare](#netlist_cur2ref_compare)
    * [netlist_flip](#netlist_flip)
    * [netlist_flip_mirror](#netlist_flip_mirror)
    * [netlist_man_reg](#netlist_man_reg)
    * [netlist_page_close](#netlist_page_close)
    * [netlist_page_open](#netlist_page_open)
    * [netlist_recalc](#netlist_recalc)
    * [netlist_ref_update](#netlist_ref_update)
    * [netlist_rotate](#netlist_rotate)
    * [netlist_save_compare_results](#netlist_save_compare_results)
    * [note_delete_all](#note_delete_all)
    * [online_page_close](#online_page_close)
    * [online_page_show](#online_page_show)
    * [open_entity](#open_entity)
    * [open_job](#open_job)
    * [optimize_levels](#optimize_levels)
    * [origin](#origin)
    * [origin_off](#origin_off)
    * [origin_on](#origin_on)
    * [output](#output)
    * [output_layer_reset](#output_layer_reset)
    * [output_layer_set](#output_layer_set)
    * [pan_center](#pan_center)
    * [pan_down](#pan_down)
    * [panel_size](#panel_size)
    * [pan_feat](#pan_feat)
    * [pan_left](#pan_left)
    * [pan_right](#pan_right)
    * [pan_up](#pan_up)
    * [print](#print)
    * [profile_poly_end](#profile_poly_end)
    * [profile_poly_seg](#profile_poly_seg)
    * [profile_poly_strt](#profile_poly_strt)
    * [profile_rect](#profile_rect)
    * [profile_to_rout](#profile_to_rout)
    * [pull_feat](#pull_feat)
    * [recover_lost_jobs](#recover_lost_jobs)
    * [remove_hole](#remove_hole)
    * [remove_vertex](#remove_vertex)
    * [rename_entity](#rename_entity)
    * [rename_layer](#rename_layer)
    * [rerout_trace](#rerout_trace)
    * [rotate_feat](#rotate_feat)
    * [rotate_step](#rotate_step)
    * [save_job](#save_job)
    * [script_record](#script_record)
    * [script_run](#script_run)
    * [sel_all_feat](#sel_all_feat)
    * [sel_break](#sel_break)
    * [sel_buffer_clear](#sel_buffer_clear)
    * [sel_buffer_copy](#sel_buffer_copy)
    * [sel_buffer_cut](#sel_buffer_cut)
    * [sel_buffer_option](#sel_buffer_option)
    * [sel_buffer_paste](#sel_buffer_paste)
    * [sel_change_atr](#sel_change_atr)
    * [sel_change_sym](#sel_change_sym)
    * [sel_change_text](#sel_change_text)
    * [sel_clear_feat](#sel_clear_feat)
    * [sel_cont2pad](#sel_cont2pad)
    * [sel_contourize](#sel_contourize)
    * [sel_cont_resize](#sel_cont_resize)
    * [sel_copy](#sel_copy)
    * [sel_copy_other](#sel_copy_other)
    * [sel_copy_repeat](#sel_copy_repeat)
    * [sel_create_profile](#sel_create_profile)
    * [sel_create_step](#sel_create_step)
    * [sel_cut_data](#sel_cut_data)
    * [sel_delete](#sel_delete)
    * [sel_delete_atr](#sel_delete_atr)
    * [sel_drawn](#sel_drawn)
    * [sel_fill](#sel_fill)
    * [sel_intersect_coord](#sel_intersect_coord)
    * [sel_invert](#sel_invert)
    * [sel_layer_feat](#sel_layer_feat)
    * [sel_line2pad](#sel_line2pad)
    * [sel_move](#sel_move)
    * [sel_move_other](#sel_move_other)
    * [sel_multi_feat](#sel_multi_feat)
    * [sel_net_feat](#sel_net_feat)
    * [sel_options](#sel_options)
    * [sel_orthogonal_stretch](#sel_orthogonal_stretch)
    * [sel_pad2outline](#sel_pad2outline)
    * [sel_pad2slots](#sel_pad2slots)
    * [sel_polarity](#sel_polarity)
    * [sel_polarity_invert](#sel_polarity_invert)
    * [sel_polyline_feat](#sel_polyline_feat)
    * [sel_ref_feat](#sel_ref_feat)
    * [sel_resize](#sel_resize)
    * [sel_resize_poly](#sel_resize_poly)
    * [sel_resize_surface](#sel_resize_surface)
    * [sel_reverse](#sel_reverse)
    * [sel_single_feat](#sel_single_feat)
    * [sel_stretch](#sel_stretch)
    * [sel_surf2outline](#sel_surf2outline)
    * [sel_transform](#sel_transform)
    * [set_attribute](#set_attribute)
    * [set_group](#set_group)
    * [set_out_name_attr](#set_out_name_attr)
    * [show_form](#show_form)
    * [skip_current_command](#skip_current_command)
    * [skip_next_pre_hook](#skip_next_pre_hook)
    * [snap_features](#snap_features)
    * [snap_layer](#snap_layer)
    * [snap_mode](#snap_mode)
    * [split_edge](#split_edge)
    * [sr_active](#sr_active)
    * [sr_auto](#sr_auto)
    * [sr_auto_class](#sr_auto_class)
    * [sr_auto_popup](#sr_auto_popup)
    * [sr_copy_step](#sr_copy_step)
    * [sr_del_step](#sr_del_step)
    * [sredit_popup](#sredit_popup)
    * [sr_fill](#sr_fill)
    * [sr_gold_side](#sr_gold_side)
    * [sr_make_step_grid](#sr_make_step_grid)
    * [sr_move_step](#sr_move_step)
    * [sr_pack_steps](#sr_pack_steps)
    * [sr_popup](#sr_popup)
    * [sr_reduce_nesting](#sr_reduce_nesting)
    * [sr_replace_step](#sr_replace_step)
    * [sr_sredit_sel_area_end](#sr_sredit_sel_area_end)
    * [sr_sredit_sel_area_start](#sr_sredit_sel_area_start)
    * [sr_sredit_sel_area_xy](#sr_sredit_sel_area_xy)
    * [sr_sredit_sel_clear](#sr_sredit_sel_clear)
    * [sr_sredit_sel_step_xy](#sr_sredit_sel_step_xy)
    * [sr_tab_add](#sr_tab_add)
    * [sr_tab_break](#sr_tab_break)
    * [sr_tab_change](#sr_tab_change)
    * [sr_tab_del](#sr_tab_del)
    * [stretch_feat](#stretch_feat)
    * [tools_close](#tools_close)
    * [tools_list_add](#tools_list_add)
    * [tools_list_reset](#tools_list_reset)
    * [tools_list_set](#tools_list_set)
    * [tools_merge_ex](#tools_merge_ex)
    * [tools_set](#tools_set)
    * [tools_show](#tools_show)
    * [truncate_layer](#truncate_layer)
    * [undo](#undo)
    * [units](#units)
    * [update_dependent_step](#update_dependent_step)
    * [user_delete](#user_delete)
    * [user_edit](#user_edit)
    * [wheel_current](#wheel_current)
    * [wheel_page_close](#wheel_page_close)
    * [work_layer](#work_layer)
    * [zoom_area](#zoom_area)
    * [zoom_back](#zoom_back)
    * [zoom_home](#zoom_home)
    * [zoom_in](#zoom_in)
    * [zoom_out](#zoom_out)
    * [zoom_pv_close](#zoom_pv_close)
    * [zoom_pv_move](#zoom_pv_move)
    * [zoom_pv_open](#zoom_pv_open)


---
<h2 id="overview">Overview</h2>

所有 ezCAM 支援的 Command 參考手冊，包含指令功能說明、參數型態、作用條件等。


---
#All Commands

<h2 id="add_arc">add_arc</h2>


|----|----|
|Command |add_arc|
|Group |Graphic Editor|
|Descr.| Adds an arc feature to all the affected layers. In addition to the specified parameters the current attributes are added as well (attributes that were set by the **cur_atr_set** command).|
|Response| Index of the last added features index|

|----|----|
|Parameter|Value|
|attributes| Yes - add the current attributes <br> No - no attributes|
|xc, yc| Legal coordinates - arc center|
|xs, ys| Legal coordinates - arc start|
|xe, ye| Legal coordinates - arc end|
|symbol| Existing symbol name|
|polarity| Positive, negative|
|direction| CW, CCW|

<h2 id="add_line">add_line</h2>
|----|----|
|Command |add_line|
|Group |Graphic Editor|
|Descr.|Adds a line feature to all the affected layers. In addition to the specified parameters the current attributes are added as well (attributes that were set by the cur_atr_set command).|
|Response| Index of the last added features index|

|----|----|
|Parameter| Value|
|attributes| Yes - add the current attributes <br>  No - no attributes
|xs, ys,<br> xe, ye|Legal coordinates - start and end points|
|symbol| Existing symbol name|
|polarity| Positive, negative|




<h2 id="add_pad">add_pad</h2>
|----|----|
|Command| add_pad|
|Group| Graphic Editor|
|Descr.| Adds a pad feature to all the affected layers. In addition to the specified parameters the current attributes are added as well (attributes that were set by the cur_atr_set command).|
|Response| Index of the last added features.|

|----|----|
|Parameter| Value|
|attributes| Yes - add the current attr <br> No - no attributes
|x, y| Legal coordinates - pad location|
|symbol| Existing symbol name|
|polarity| Positive, negative|
|angle| 0, 90, 180, 270|
|mirror| Yes, No - around X axis|
|nx, ny| nx, ny >= 1<br>number of pads in matrix|
|dx, dy| dx, dy >= 0 (mils) <br> matrix delta|
|x scale, <br> y scale |> 0 - in this case the pad will be broken|

<h2 id="add_polyline_crv">add_polyline_crv</h2>
|----|----|
|Command| add_polyline_crv|
|Group| Graphic Editor|
|Descr.| Adds a polyline curve points|
|Response| None|

|----|----|
|Parameter| Value|
|xc, yc| Legal coordinates for arc center point|
|xe, ye| Legal coordinates for arc end point|
|cw|yes - clockwise <br> no - counter clockwise|


<h2 id="add_polyline_end">add_polyline_end</h2>
|----|----|
|Command| add_polyline_end|
|GroupGraphic| Editor|
|Descr.|Closes a polyline (series of line features).|
|Response| None|

|----|----|
|Parameter| Value|
|attributes| Yes - add the current attr <br> No - no attributes|
|symbol| Existing symbol name|
|polarity| Positive, negative|



<h2 id="add_polyline_strt">add_polyline_strt</h2>
|----|----|
|Command| add_polyline_strt|
|Descr.| Starts polyline.|
|Group |Graphic Editor|
|Response| None|


<h2 id="add_polyline_xy">add_polyline_xy</h2>
|----|----|
|Command| add_polyline_xy|
|Group| Graphic Editor|
|Descr.| Adds a polyline point.|
|Response| None|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates|


<h2 id="add_slot">add_slot</h2>
|----|----|
|Command| add_slot|
|Group| Graphic Editor|
|Descr.| Adds slot feature (= a line with its .drill_type attribute set) to all the affected layers.|
|Response |None|

|----|----|
|Parameter| Value|
|symbol| A legal line symbol name - example: r201|
|x_center,<br> y_center|  Legal coordinates - slots middle point (inch/mm)|
|len| Positive value - slot len (inch/mm)|
|angle| Positive integer (0 - 360) - slot angle (degree)|
|dcode| Positive integer (0 -> none) - slot dcode|
|drill_type| Plate - plated hole <br> nplate - non-plated hole <br> via - via hole





<h2 id="add_surf_end">add_surf_end</h2>
|----|----|
|Command |add_surf_end|
|Group| Graphic Editor|
|Descr.| The command closes a surface, and adds it to the work and affected layers.|
|Response| Index of the last added features index|

|----|----|
|Parameter| Value|
|attributes| Yes - add the current attributes <br> No - no attributes|
|polarity| Positive, negative|



<h2 id="add_surf_hole_end">add_surf_hole_end</h2>
|----|----|
|Command| add_surf_hole_end|
|Group| Graphic Editor|
|Descr.|The command closes a surface hole|
|Response|None|


<h2 id="add_surf_hole_strt">add_surf_hole_strt</h2>
|----|----|
|Command| add_surf_hole_strt|
|Group| Graphic Editor|
|Descr.| The command starts a surface polygon|
|Response| None|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - start point|

<h2 id="add_surf_poly_crv">add_surf_poly_crv</h2>
|----|----|
|Command| add_surf_poly_crv|
|Group| Graphic Editor|
|Descr.| Adds a polygon curve.|
|Response| None|

|----|----|
|Parameter| Value|
|xc, yc| Legal coordinates - curve center point|
|xe, ye| Legal coordinates - curve end point|
|cw| Yes - clockwise <br> No - counter clockwise


<h2 id="add_surf_poly_end">add_surf_poly_end</h2>
|----|----|
|Command| add_surf_poly_end|
|Group| Graphic Editor|
|Descr.| Closes a surface polygon.|
|Response| None|


<h2 id="add_surf_poly_seg">add_surf_poly_seg</h2>
|----|----|
|Command| add_surf_poly_seg|
|Group| Graphic Editor|
|Descr.| Adds a polygon segment.|
|Response| None|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - segment end point|


<h2 id="add_surf_poly_strt">add_surf_poly_strt</h2>
|----|----|
|Command| add_surf_poly_strt|
|Group| Graphic Editor|
|Descr.|Starts a surface polygon.|
|Response| None|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - start point|


<h2 id="add_surf_strt">add_surf_strt</h2>
|----|----|
|Command| add_surf_strt|
|Group| Graphic Editor|
|Descr.| Starts a surface feature.|
|Response| None|


<h2 id="add_text">add_text</h2>
|----|----|
|Command| add_text|
|Group| Graphic Editor|
|Descr.| Adds a text feature to all the affected layers. In addition to the specified parameters the current attributes are added as well (attributes that were set by the cur_atr_set command). The added text feature may be a string, barcode, or canned text.|
|Response| Index of the last added features index|

|----|----|
|Parameter| Value|
|attributes| Yes - add the current attr <br> No - no attributes|
|type|String, barcode, orb_plot_stamp_str, orb_plot_stamp_bar, canned_text|
|x, y| Legal coordinates - text position|
|text| Free text - text string (may be a dynamic text)|
|x_size,<br> y_size| 0 < size < 0.2 inches - character size relevant if type = ‘string’|
|w_factor| 0.0 < w_factor - font line width factor relevant if type ==‘string’|
|polarity| Positive, negative|
|angle| 0, 90, 180, 270|
|mirror| Yes, No - around X axis|
|fontname| Must be ‘standard’ - at this stage only the standard font is supported|
|bar_type| upc39 - relevant if type = ‘barcode’|
|bar_char <br> _set| ASCII, full_ascii|
|bar_ <br> checksum| Yes - add checksum info <br> No - no checksum info|
|bar_ <br> background| Yes, No|
|bar_add_string|Yes - addition text string <br> No - no string
|bar_add_ <br> string_pos| Top, bottom|
|bar_width| Width > 0 (inches) - element width|
|bar_height| Height > 0 (inches) - barcode height|
|bar_marks| If yes (default), corner marks are added to ECC-200 barcodes. <br> If no, corner marks are not added to ECC-200 barcodes.|
|ver| 0 - old version <br> 1 - new text version - (only for the version controls scripts compatibility the position of the text <br>The version controls the position of the text.|
|matrix| The additional parameter **Matrix** can be used when you select the barcode type ECC-200. (All other barcode types do not show this extra parameter.<br>**Matrix** can receive any of the following values:|


    8x18 12x12 14x14 16x48 22x22 32x32 44x44 64x64 80x80
    
    8x32 12x26 16x16 18x18 24x24 36x36 48x48 72x72 88x88
    
    10x10 12x36 16x36 20x20 26x26 40x40 52x52 96x96
    
    104x104 120x120 132x132 144x144



<h2 id="affected_filter">affected_filter</h2>
|----|----|
|Command| affected_filter|
|Group| Graphic Editor|
|Descr.| Used for setting the affected layers according to a special filter. The filter is a textual string that contains the layer type, context, side and polarity. The format is the same as for the dfm layer filter.|
|Response| None|

|----|----|
|Parameter| Descr.|
|filter| Layers filter|


<h2 id="affected_layer">affected_layer</h2>
|----|----|
|Command| affected_layer|
|Group| Graphic Editor|
|Descr.| Sets/unsets affected layers.|
|Response| None|

|----|----|
|Parameter| Value|
|name| Entity name|
|mode| Single - according to ‘name’<br> All - set all step layers <br> Board - set the board layers <br> (matrix context == ‘board’)|
|affected| Yes - set to be affected <br> No - unset the layer(s)|



<h2 id="autopanel_ezplan">autopanel_ezplan</h2>
|----|----|

無

<h2 id="autopanel_fpc">autopanel_fpc</h2>
|----|----|
無
<h2 id="autopanel_fpc_popup">autopanel_fpc_popup</h2>
|----|----|
無
<h2 id="autopanel_fpc_seterf">autopanel_fpc_seterf</h2>
|----|----|
無

<h2 id="autopanel_fpc_setparameter">autopanel_fpc_setparameter</h2>
無
<h2 id="break_feat">break_feat</h2>
|----|----|
|Command| break_feat|
|Group| Graphic Editor|
|Descr.| Breaks the feature into two features at the selected point.|
|Response| None|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer|
|x, y| Legal coordinates of feature coordinates|
|length| Length of break in mils|
|tol| Snap tolerance. Value range: 0 <= tol (mils)|



<h2 id="cadnet_reduce_points_to_center">cadnet_reduce_points_to_center</h2>

|----|----|
|Command| cadnet_reduce_points_to_center_comm|
|Group| CAMTEK AOI|
|Descr.| The command reduces the CAD netlist points dimension to a default radius of 0.2 mil.|
|Response| 1 on success, 0 on failure|


|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|radius| Radius of reduced net points. Value in mils.|


<h2 id="chain_add">chain_add</h2>

|----|----|
|Command| chain_add|
|Group| Graphic Editor|
|Descr.| The routine is used for a adding a new rout chain. The selected features are taken to be part of the chain.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer|
|chain| Chain >= 1|
|size| Tool size (inch)|
|comp| None, left, right - Rout compensation|
|flag| Special rout flag >= 0|
|feed| Feed Rate >= 0|
|speed| Spindle speed >= 0|
|first| First f|
|chng_<br>direction| If to change dir of first f|



<h2 id="chain_add_pilot">chain_add_pilot</h2>

|----|----|
|Command| chain_add_pilot|
|Group| Graphic Editor|
|Descr.| The routine is used for adding pilot holes in a list of rout chains.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|
|pilot size| Tool size in inch|





<h2 id="chain_append">chain_append</h2>

|----|----|
|Command| chain_append|
|Group| Graphic Editor|
|Descr.| The routine is used for a appending a new rout chain. The selected features are taken to be part of the chain.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer|
|after| Feature to add after|



<h2 id="chain_change">chain_change</h2>

|----|----|
|Command| chain_change|
|Group| Graphic Editor|
|Descr.| The routine is used for changing the parameters of an existing rout chain.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer|
|size| Tool size (inch)|
|comp| None, left, right - Rout compensation|
|flag| Special rout flag >= 0|
|feed| Feed Rate >= 0|
|speed| Spindle speed >= 0|



<h2 id="chain_change_dir">chain_change_dir</h2>

|----|----|
|Command| chain_change_dir|
|Group| Graphic Editor|
|Descr.| The routine is used for changing the direction of a chain.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|


<h2 id="chain_change_num">chain_change_num</h2>

|----|----|
|Command| chain_change_num|
|Group Graphic| Editor|
|Descr.| The routine is used for changing the chain number.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|
|chain| Chain >= 1|
|new_chain| Chain >= 1|
|renumber_sequentially|Values = [no/yes] (default = no)|


<h2 id="chain_del_pilot">chain_del_pilot</h2>

|----|----|
|Command| chain_del_pilot|
|Group| Graphic Editor|
|Descr.| The routine is used for deleting pilot holes in a list of rout chains.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|



<h2 id="chain_insert">chain_insert</h2>

|----|----|
|Command| chain_insert|
|Group| Graphic Editor|
|Descr.| The routine is used for inserting rout chains into others|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|
|renumber_<br> sequentially| Values = [no/yes] (default = no)|


<h2 id="chain_list_add">chain_list_add</h2>

|----|----|
|Command| chain_list_add|
|Group| Graphic Editor|
|Descr.| The routine is used for adding a chain number to a list, that is used by some of the other ‘chain’ line mode commands (e.g: chain_cancel, chain_change).|


|----|----|
|Parameter| Value|
|chain| Chain >= 1|


<h2 id="chain_list_reset">chain_list_reset</h2>

|----|----|
|Command| chain_list_reset|
|Group| Graphic Editor|
|Descr.|The routine is used for resetting the ‘chains’ list, that is used by some of the other ‘chain’ line mode commands (e.g chain_cancel, chain_change).|


<h2 id="chain_merge">chain_merge</h2>

|----|----|
|Command:| chain_merge|
|Group| Graphic Editor|
|Descr.| The routine is used for merging a list of rout chains.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|
|renumber_<br>sequentially|Values = [no/yes] (default = no)|



<h2 id="chain_pocket">chain_pocket</h2>

|----|----|
|Command| chain_pocket|
|Group| Graphic Editor|
|Descr.| The routine is used for setting the pocket of a chain.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer|
|mode| Pocket mode (delete/concentric)|
|size| Tool size for pocketing (current units)|
|feed| Feed Rate >= 0|
|overlap| Overlap size (current units)|
|pocket_dir| Sets pocket direction (Standard; Opposite)|


<h2 id="chain_set_plunge">chain_set_plunge</h2>

|----|----|
|Command| chain_set_plunge|
|Group| Graphic Editor|
|Descr.|The routine is used for setting the plunge of a chain.|


|----|----|
|Parameter |Value|
|layer| Existing rout layer name
|type| Corner/inline/open
|mode| According to type straight / chamfer / arc
|inl_mode| straight; overlap; arc; diag; diag_ang (only for type = inline)|
|len1| Length of offsets (inch)
|len2| Length of offsets (inch)
|len3| Length of offsets (inch)
|len4|Length of offsets (inch)
|val1| Length of offsets (inch)
|val2| Length of offsets (inch)
|ang1| Angle (grad)
|ang2| Angle (grad)
|ifeed| Plunge Feed Rate >= 0
|ofeed| Cutoff Feed Rate >= 0
|start_of_<br>chain| Defines whether the start of the chain moves to the plunge <br> Yes = Start of chain moves to the plunge <br>No = Start of chain does not move to the plunge|
|apply_to| Defines the connected feature sequences to which the plunge will be added.<br>Possible values include: <br> all closed/closed_int/closed_ext|



<h2 id="chain_split">chain_split</h2>

|----|----|
|Command:| chain_split|
|Group| Graphic Editor|
|Descr.|The command is used for splitting a selected chain into sequences of connected features and creation of a separate chain for each sequence.|

|----|----|
|Parameter| Value|
|layer| Existing rout layer name|
|chain| chain number (Must be 1 or larger)|
|mode| subchains - splitting sequences of connected features and creating a separate chain for each sequence <br> from_feat - splitting into two chains where the second chain begins from the selected one <br> extract - splitting into two chains where second chain includes all selected features|
|renumber_<br>sequentially| Values = [no/yes] (default = no)|


<h2 id="change_edge">change_edge</h2>

|----|----|
|Command:| change_edge|
|Group| Graphic Editor|
|Descr.|Transformation of a contour vertex.|

|----|----|
|Parameter| Value|
|edge_x,<br>edge_y|Legal coordinates (inches/mm) - coordinates of a point on edge (before change).|
|new_type| Segment / curve - new type of edge.|
|new_center<br>_[xy]| Legal coordinates (inches/mm) - new center’s coordinates (used only if edge is a curve).|
|new_cw| Clockwise / counter clockwise - new direction of edge (used only if edge is a curve).|


<h2 id="change_step_dependency">change_step_dependency</h2>

|----|----|
|Command:| change_step_dependency|
|Group| Engineering Toolkit (Job Matrix)|
|Descr.| Parameter Value|
|job| Legal job name|
|step| Legal step name|
|operation| Values: release, restore|




<h2 id="check_inout">check_inout</h2>


|----|----|
|Command| check_inout|
|Group| Locks Manager|
|Descr.| Used for Checking In/out elements|
|Response| If mode = test: no - not checked out <br>yes <user> - checked out by user|

|----|----|
|Parameter| Value|
|mode| In, out, test|
|type| Job, step, layer, symbol, stack, wheel, matrix, form, flow, font template, path|
|job| Job name|
|step| Step name - job must be defined|
|layer| Layer name - job and step must be defined|
|symbol| Symbol name - job must be defined|
|stackup| Stackup name - job must be defined|
|matrix| Matrix name - job must be defined|
|wheel| Wheel name - job must be defined|
|form| Form name|
|flow| Flow name|
|template| Template name|
|font| Font name|
|path| Any path - can be used by user|



<h2 id="chklist_cdel">chklist_cdel</h2>

|----|----|
|Command| chklist_cdel|
|Group| Graphic Editor|
|Descr.| Deletes an action from a checklist|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action number|



<h2 id="chklist_close">chklist_close</h2>

|----|----|
|Command| chklist_close|
|Group| Graphic Editor|
|Descr.| Closes an action display page|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|mode| Hide - Only hide the page<br>Destroy - Destroys the displayed page <br> Unload_res - destroy the displayed page and free all memory occupied by results. <br>Note: You must save the job if you wish to store the checklist results. Otherwise after this command is executed with mode= unload_res, checklist results will be lost.|




<h2 id="chklist_create">chklist_create</h2>

|----|----|
|Command| chklist_create|
|Group| Graphic Editor|
|Descr.| Creates a new checklist entity. If a checklist by this name exists, it is overwritten.|
|Response| None|

|----|----|
|Parameter| Value|
|chklist| Entity name|



<h2 id="chklist_cupd">chklist_cupd</h2>

|----|----|
|Command| chklist_cupd|
|Group| Graphic Editor|
|Descr.|Updates the parameters of an action in a checklist|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action number|
|params| A string - representing the parameters of the check|
|mode| Regular or online|




<h2 id="chklist_erf">chklist_erf</h2>

|----|----|
|Command| chklist_erf|
|Group| Graphic Editor|
|Descr.| Updates the ERF model of an action in a checklist|


|----|----|
|Paramete|Value|
|chklist| Entity name|
|nact| Action number|
|erf| The name of the ERD model|


<h2 id="chklist_from_lib">chklist_from_lib</h2>

|----|----|
|Command| chklist_from_lib|
|Group| Graphic Editor|
|Descr.| Copies a checklist from the library to the job (entity must not exist in the job)|

|----|----|
|Parameter| Value|
|chklist| Entity name|




<h2 id="chklist_hist_close">chklist_hist_close</h2>

|----|----|
|Command| chklist_hist_close|
|Group|Graphic Editor|
|Descr.| Closes the histogram of an action in a checklist

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action numbe|


<h2 id="chklist_hist_show">chklist_hist_show</h2>

|----|----|
|Command| chklist_hist_show|
|Group| Graphic Editor|
|Descr.|Shows the histogram of an action in a checklist|

|----|----|
|Parameter|Value|
|chklist|Entity name|
|nact|Action number|



<h2 id="chklist_pclear">chklist_pclear</h2>

|----|----|
|Command| chklist_pclear|
|Group| Graphic Editor|
|Descr.|clears the paste buffer|


<h2 id="chklist_pcopy">chklist_pcopy</h2>

|----|----|
|Command| chklist_pcopy|
|Group| Graphic Editor|
|Descr.|Copies an action from the checklist to the paste buffer.|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| The number of action|


<h2 id="chklist_ppaste">chklist_ppaste</h2>

|----|----|
|Command| chklist_ppaste|
|Group| Graphic Editor|
|Descr.|Copies an action from the paste buffer to the checklist|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|row| The row to insert the check - (0 = last)|


<h2 id="chklist_res_close">chklist_res_close</h2>

|----|----|
|Command| chklist_res_close|
|Group| Graphic Editor|
|Descr.|Closes the results of an action in a checklist|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action number|
|mode| Close - action results are being unloaded from memory.<br>Hide - result viewer gets hidden.


<h2 id="chklist_res_exp">chklist_res_exp</h2>

|----|----|
|Command| chklist_res_exp|
|Group| Graphic Editor|
|Descr.| Exports the report of an action to a file or printer|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action number|
|source| All, report or attributes|
|dest| Printer or file|
|fname| Name of file to create file (in /genesis/tmp)|





<h2 id="chklist_res_show">chklist_res_show</h2>

|----|----|
|Command| chklist_res_show|
|Group| Graphic Editor|
|Descr.|Shows the results of an action in a checklist|

|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| Action number|
|x| x coordinate for window|
|y| y coordinate for window|
|w| Width for window|
|h| Height for window|



<h2 id="chklist_run">chklist_run</h2>

|----|----|
|Command| chklist_run|
|Group| Graphic Editor|
|Descr.|Runs all or part of the checklist actions|


|----|----|
|Parameter| Value|
|chklist| Entity name|
|nact| a - run all checks <br>u - run out of date checks <br>s - run selected checks
|area| Global - all step area <br> Local - only screen area <br>  Profile - only inside profile



<h2 id="chklist_show">chklist_show</h2>

|----|----|
|Command| chklist_show|
|Group| Graphic Editor|
|Descr.| Shows the checklist page (Use after close with hide)|

|----|----|
|Parameter| Value|


<h2 id="chklist_single">chklist_single</h2>

|----|----|
|Command| chklist_single|
|Group|Graphic Editor|
|Descr.|Pops up a single DFM or ANALYSIS window for operating an Analysis or DFM action <br> NOT within a checklist.|

|----|----|
|Parameter| Value|
|action| Action name|
|show| Yes - display the screen <br> No - do not display|


<h2 id="chklist_to_layer">chklist_to_layer</h2>
|----|----|
無
|----|----|
<h2 id="clear_highlight">clear_highlight</h2>

|----|----|
|Command| clear_highlight|
|Group| Graphic Editor|
|Descr.|Clears the features highlight display.|


<h2 id="clear_layers">clear_layers</h2>

|----|----|
|Command| clear_layers|
|Group|Graphic Editor|
|Descr.|Clears the display of all the layers.|


<h2 id="clip_area_end">clip_area_end</h2>

|----|----|
|Command| clip_area_end|
|Group|Graphic Editor|
|Descr.|The command closes the clip area, and executes on the specified layers.|

|----|----|
|Parameter| Value|
|layers_mode|layer_name - specified dest layer<br>affected_layers - copy to all the affected layers
|layer| Entity name - if (layers_mode = layer_name)|
|area| Manual, profile|
|area_type| Rectangle, polygon - if (area = manual)|
|inout| Inside, outside|
|contour_<br>cut|Cut features touching border via contour operation or like lines, pads etc.|
|margin| In mils|

<h2 id="clip_area_strt">clip_area_strt</h2>

|----|----|
|Command| clip_area_strt|
|Group|Graphic Editor|
|Descr.|Command for starting a clip area|

<h2 id="clip_area_xy">clip_area_xy</h2>

|----|----|
|Command| clip_area_xy|
|Group|Graphic Editor|
|Descr.|Command for adding a polygon/rectangle point.|

|----|----|
|Parameter| Value|
|x, y| Legal x, y coordinates|


<h2 id="clipb_open_job">clipb_open_job</h2>

|----|----|
|Command| clipb_open_job|
|Group|Engineering Toolkit|
|Description| The clipb_open_job command is used to open a job (reading it from the database into the memory) and change the clipboard view.|

|----|----|
|Parameter| Value|
|job| Existing job name|
|update___<br>clipboard|no - (default) does not update        clipboard <br> view_job - changes a clipboard to view the job entities (matrix, steps, symbols, ets.) <br> new_window - opens the job in a separate clipboard window



<h2 id="close_flow">close_flow</h2>

|----|----|
|Command| close_flow|
|Group|Work Flows|
|Descr.|Closes a given flow|

|----|----|
|Parameter| Value|
|job| Name of the job|
|flow| Name of the flow|



<h2 id="close_form">close_form</h2>

|----|----|
|Command| close_form|
|Group| Work Forms|
|Descr.|Closes a given form|

|----|----|
|Parameter| Value|
|job| Name of the job|
|form| Name of the form|


<h2 id="close_job">close_job</h2>

|----|----|
|Command| close_job|
|Group| Engineering Toolkit
|Descr.| Used for closing a job in the memory (releasing the allocated memory and closing the editing session).<br> If the job was changed in the memory, the changes will be lost.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|



<h2 id="colors_change">colors_change</h2>

|----|----|
|Command| colors_change|
|Group|Graphic Editor|
|Description|The command is used for changing a color of a single plane.|
|Response|Previous color of the plane in rrggbb format.|


|----|----|
|Parameter| Description|
|Plane| Plane name from the list: bg,l1,l2,l3,l4,rb,hl,sl|
|color| New plane color in rrggbb format. <br> Range - 000000 .. 999999|




<h2 id="colors_restore">colors_restore</h2>

|----|----|
|Command| colors_restore|
|Group|Graphic Editor|
|Description|The command is used to restore previously stored colors of all planes.|


<h2 id="colors_set">colors_set</h2>

|----|----|
|Command| colors_set|
|Group|Graphic Editor|
|Command<br>Description|The colors_set command is used for setting the user colors in system mode. You can switch between a user-saved color scheme and system color values.|

|----|----|
|Parameter| Value|
|mode| Sets user mode. Possible values: user, system, default.<br>Default mode uses color scheme that is found (in order from first to last) in user/host/system.


<h2 id="colors_store">colors_store</h2>

|----|----|
|Command| colors_store|
|Group|Graphic Editor|
|Description|The command is used for storing the current colors of all planes for future restorations.|




<h2 id="compare_layers">compare_layers</h2>

|----|----|
|Command| compare_layers|
|Group| Graphic Editor|
|Descr.|The command is used for performing a picture (pix by pix) compare between 2 layers.|
|Response| The number of boxes that have differences. If there are no differences the response will be 0.|

|----|----|
|Parameter| Value|
|layer1| Layer in the current step|
|job2| Name of second job|
|step2| Can be a different step in the same job|
|layer2| Second layer name|
|layer2_ext|-----|
|tol| 0.03 <= tol <= 10 mils. Default=1 mil|
|map_layer| Legal layer name|
|map_layer_res| 10 <= map_layer_res <= 1000 mils. Default=200 mils.|



<h2 id="compensate_layer">compensate_layer</h2>

|----|----|
|Command| compensate_layer|
|Group|Graphic Editor|
|Descr.|The command compensates the source layer and creates a new layer (dest_layer) with the compensated features.|

|----|----|
|Parameter| Value|
|source_<br>layer|Entity name|
|dest_<br>layer|Entity name - destination layer|
|dest_layer_<br>type|Destination layer type <br>Rout - Destination layer will be created of type Rout and all rout attributes will be saved.<br>Document - Destination layer will be created of type Document and all rout attributes will be deleted|



<h2 id="copper_area">copper_area</h2>

|----|----|
|Command| copper_area|
|Group|Graphic Editor|
|Descr.|The command calculates the copper area of a layer (s). The operation is performed on the raster image of the layer. The distribution map and the thermal map are created for the user interface popup, and cannot be accessed through the command (at this stage...).|
|Response|Contains the total copper value + the copper percentage.<br> Syntax: ccccc ppppp (ccccc - copper area, ppppp -percentage).|


|----|----|
|Parameter| Value|
|layer1| Existing layer name|
|layer2| Existing layer name|
|drills| Yes - take the drill layers into account the drill layers are taken according to job matrix <br>No - no drill layers|
|drills_<br>source|Matrix - take from matrix<br>Manual - take the list of drills rather than from the matrix|
|resolution| 1/4, 1/2, 1 mils - rasterization resolution|
|resolution_<br>value|Resolution value in the current units. Range [1mic ... 2mil ]<br>Note: (used only if parameter resolution not defined).|
|thickness| 0 <= thickness - used for calculating drill cylinder area|
|x_boxes,<br>y_boxes| 1 <= num <= 200 - number of boxes for the distribution map|
|area| Yes - use the specified area (x1, y1, x2, y1) <br>No - copper area for the whole layer
|x1, y1,<br>x2, y2|Legal coordinates - rectangle corners
|dist_map| Yes - create distribution map <br> No - no distribution map|
|f_type| All - all features<br>Selected - only selected features|
|out_file| Output file (optional)|
|out_layer| First / second / sum - what layer to display in out_file.|
|consider_<br>rout|Yes: rout features are considered when calculating the copper area.<br>No: rout features are not considered when calculating the copper area.<br>Note: This feature is implemented only if the parameter drill=yes in either line mode command copper_area or exposed_area.|
|edges| Values = [no/yes] (default = no). If yes, consider copper edges when calculating total copper area in a layer.|
|consider<br>_thickness|Thickness of copper edge areas. Values = [0..Max Coordinate] in mil/my.<br>Useful only when edges=yes.|




<h2 id="copy_entity">copy_entity</h2>

|----|----|
|Command| copy_entity|
|Group|Engineering Toolkit|
|Descr.|Used for copying an entity. If the target entity already exists, it will be overwritten.|

|----|----|
|Parameter| Value|
|type| Job, step, symbol, stackup, wheel, matrix|
|source_job| Existing job name|
|source_name| Existing entity name|
|dest_job| Existing job name - only if type!= job
|dest_name| Entity name|
|dest_database| Specifies the destination database name. Used only if type is job.|


<h2 id="copy_feat">copy_feat</h2>

|----|----|
|Command| copy_feat|
|Group|Graphic Editor|
|Descr.|Copies a feature in all the affected layers.|

|----|----|
|Parameter |Value|
|index| Feature index in the work layer.(Optional)If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|dx, dy| Legal coordinates - shift values|
|tol| 0 <= tol (mils) - snap tolerance|



<h2 id="copy_form">copy_form</h2>

|----|----|
|Command| copy_form|
|Group|WorkForms|
|Descr.|Copies forms between jobs|

|----|----|
|Parameter|Value|
|src_job Job| to copy from|
|src_form| Form to copy from|
|dst_job| Job to copy to|
|dst_form|Form to copy to|


<h2 id="copy_layer">copy_layer</h2>

|----|----|
|Command| copy_layer|
|Group|Graphic Editor|
|Descr.|The command copies a layer to another layer. If the destination layer does not exist, it will be created and added to end of the matrix.|

|----|----|
|Parameter| Value|
|source_job| Existing job name|
|source_step|Entity name - from the job or from the library|
|source_layer|Entity name - dest|
|dest layer_name| - Specified dest layerEntity name - destination layer<br>affected_ layers - Copy to all the affected layers|
|dest_layer| Entity name|
|mode| Replace - replace the dest layer(s)<br>Append - add to the end of dest layer(s)|
|invert| Yes - invert the features polarity <br> No - no invert|



<h2 id="create_entity">create_entity</h2>

|----|----|
|Command| create_entity|
|Group|Engineering Toolkit|
|Descr.|Used for creating entities.|

|----|----|
|Parameter |Value|
|job| Name of an existing opened job|
|is_fw| Yes - framework entity (form, flow- according to the ‘fw_type’ parameter)<br>No - CAM entity (according to the ‘type’ param)|
|type| Job, step, symbol, stackup, wheel, matrix| 
|fw_type| Form, flow|
|name| Legal entity name|
|db| Db name (in case of job)|




<h2 id="create_layer">create_layer</h2>

|----|----|
|Command| create_layer|
|Group|Graphic Editor|
|Descr.|The command is used for creating a new layer.|

|----|----|
|Parameter| Value|
|layer| New layer name|
|context| Board, misc|
|type| Signal, solder_mask,,,,etc|
|polarity| Positive, negative|
|ins_layer| Existing layer or EMPTY string - for adding the layer to the end of the list|
|location| Values: [ before; after ] Default = before, to ensure backwards compatibility|



<h2 id="cre_drills_map">cre_drills_map</h2>

|----|----|
|Command| cre_drills_map|
|Group|Graphic Editor|
|Descr.|The command creates a layer with markers that represent the drills. On the right bottom side there is a summary table.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|
|map_layer|------|
|preserve_<br>attr|Yes - all feature attributes are copied to the corresponding markers on the drill map layer.|
|draw_<br>origin|Yes - draws X,Y origin on drill maps <br>No -|
|units| Inch, mil, mm|
|mark_dim| Marker diameter dimension|




<h2 id="cur_atr_reset">cur_atr_reset</h2>

|----|----|
|Command| cur_atr_reset|
|Group|Graphic Editor|
|Descr.|The command resets the current attributes list.|


<h2 id="cur_atr_set">cur_atr_set</h2>

|----|----|
|Command| cur_atr_set|
|Group| Graphic Editor|
|Descr.|The command sets the current attributes list. The list issued by several command (e.g -add_pad,,,,,).|

|----|----|
|Parameter| Value|
|attribute| Existing attribute name|
|text| Free text - for text attributes|
|option| Option string - for option|
|int| Integer value - for integer|
|float| Float value - for float|




<h2 id="datum">datum</h2>

|----|----|
|Command| datum|
|Group|Graphic Editor|
|Descr.|Sets the step datum point (used for step & repeat and for the pattern fill functions).|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - datum position|


<h2 id="db_create">db_create</h2>

|----|----|
|Command| db_create|
|Group| Engineering Toolkit|
|Descr.| Create a new database entry in the local dblist.

|----|----|
|Parameter| Value|
|name| name of the database|
|path| database path|



<h2 id="db_del">db_del</h2>

|----|----|
|Command| db_del|
|Group| Engineering Toolkit|
|Descr.| Used for deleting database from the current dblist.|

<h2 id="delete_entity">delete_entity</h2>

|----|----|
|Command| delete_entity|
|Group|Engineering Toolkit|
|Descr.|Used for deleting entities.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|type| Job, step, symbol, stackup, symbol deletion is wheel, matrix - not supported at this stage|
|name| Existing entity name|


<h2 id="delete_feat">delete_feat</h2>

|----|----|
|Command| delete_feat|
|Group|Graphic Editor|
|Descr.|Deletes a feature from all the affected layers.|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Feature coordinates|
|tol| 0 <= tol (mils) - snap tolerance|
|mode| **whole** - delete entire feature.<br>**intersect** - delete part of the feature limited of the nearest intersections from both sides of the given feature ( not used on the affected layers ).|

<h2 id="delete_layer">delete_layer</h2>

|----|----|
|Command| delete_layer|
|Group|Graphic Editor|
|Descr.|The command is used for deleting an existing layer.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|



<h2 id="delete_user_file">delete_user_file</h2>

|----|----|
|Command| delete_user_file|
|Group|Engineering Toolkit|
|Descr.|Deletes files from User directory|

|----|----|
|Parameter| Value|
|job| Valid job name|
|file| Valid file name|
|mode| **single** (default) - to delete a file defined in parameter file<br>**all**- to delete all files from the user directory




<h2 id="display_chain">display_chain</h2>

|----|----|
|Command| display_chain|
|Group|Graphic Editor|
|Descr.|Sets the ‘chain’ display mode (display the chains features or not).|

|----|----|
|Parameter| Value|
|display| Yes - display the chain layer features <br>No - do not display the chain



<h2 id="display_datum">display_datum</h2>

|----|----|
|Command| display_datum|
|Group|Graphic Editor|
|Description|Sets the datum and origin display mode|

|----|----|
|Parameter| Value|
|display| Values =[no;yes]. Default=yes for compatibility|



<h2 id="display_grid">display_grid</h2>

|----|----|
|Command| display_grid|
|Group|Graphic Editor|
|Descr.|Sets the grid display mode.|

|----|----|
|Parameter |Value|
|mode| Off - no grid display<br>Marks - ‘+’ markers<br>Net - full matrix grid<br>Dots -dots
|xgrid,<br>ygrid|0 < size <= max_coord<br>grid size minimum limit = 0.1my



<h2 id="display_layer">display_layer</h2>

|----|----|
|Command| display_layer|
|Group|Graphic Editor|
|Descr.|Displays or clears a step layer.|

|----|----|
|Parameter| Value|
|name| Entity name|
|display| Yes - display the layer <br>No - clear the layer
|number| 1 - 4 - graphical plane|


<h2 id="display_profile">display_profile</h2>

|----|----|
|Command| display_profile|
|Group|Graphic Editor|
|Descr.|Sets the ‘profile’ display mode (display the profile or not).|

|----|----|
|Parameter| Value|
|display| Yes - display the profile <br> No - don’t display the prof|



<h2 id="display_sr">display_sr</h2>

|----|----|
|Command| display_sr|
|Group|Graphic Editor|
|Descr.|Sets the ‘step & repeat’ display mode (display the sr features or not).|

|----|----|
|Parameter| Value|
|display|Yes - display the step & repeat layer features<br>No - display only the step & repeat rout profiles




<h2 id="display_width">display_width</h2>

|----|----|
|Command| display_width|
|Group|Graphic Editor|
|Descr.|Sets the display width mode.|

|----|----|
|Parameter| Value|
|mode| On - full width<br>Outline - outline display <br>Off - skeleton display




<h2 id="disp_off">disp_off</h2>

|----|----|
|Command| disp_off |
|Group| Engineering Toolkit|
|Descr.| Switch the display off|



<h2 id="disp_on">disp_on</h2>

|----|----|
|Command| disp_on|
|Group|Engineering Toolkit|
|Descr.|switch the display on|



<h2 id="disp_snapshot">disp_snapshot</h2>

|----|----|
|Command| disp_snapshot|
|Group| Graphic Editor|
|Descr.|Enables user to make a snapshot of the current graphic editor view and write it to a JPG file. If picture width and/or height is specified, the snapshot is scaled to fit the specified dimensions. If one or both dimension parameters are not specified, the graphic’s current size is used.<br>Examples below:<br>COM disp_snapshot,file=/tmp/n1.jpg<br>This line copies the graphic area to the file /tmp/n1.jpg.<br>COM disp_snapshot,file=/tmp/n2.jpg,width=1000,height=1000<br>This line scales the graphic area and copy it to the file/tmp/n2.jpg

|----|----|
|Parameter| Value|
|file| Full path name of the jpg file to save the graphic into (including .jpg file extension)|
|width| Width of the picture in pixels|
|height| Height of the picture in pixels|



<h2 id="duplicate_entity">duplicate_entity</h2>

|----|----|
|Command| duplicate_entity|
|Group|Engineering Toolkit|
|Descr.|Used for duplicating entities. A new entity is created with a name that is an extension of the specified name. The specified entity is then copied to the new entity.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|type| Job, step, symbol, stackup, wheel, matrix|
|name| Existing entity name|



<h2 id="editor_group">editor_group</h2>

|----|----|
|Command| editor_group|
|Group|Engineering Toolkit|
|Descr.|The command is used for getting the editor group of a specified step/symbol. The group number is important in scripts, where the group number must be specified.|
|Response|Group number or -1 if the entity does not have an open editor|

|----|----|
|Parameter| Value|
|job| Existing job name|
|is_step| Yes - step<br>No - symbol|
|name| Existing step/symbol name|



<h2 id="editor_page_close">editor_page_close</h2>

|----|----|
|Command| editor_page_close|
|Group|Graphic Editor|
|Descr.|Closes / hides the editor page.|


<h2 id="export_job">export_job</h2>

|----|----|
|Command| export_job|
|Group|Engineering Toolkit|
|Descr.|Performs automatic export of Genesis 2000 job


|----|----|
|Parameter| Value|
|job| Name of job to export|
|path| Directory to export job to|
|mode| tar_gzip, tar, directory|
|units| Values = "metric", "imperial". Only for XML|
|submode| Values = "full", "partial". Only for XML|



<h2 id="exposed_area">exposed_area</h2>

|----|----|
|Command| exposed_area|
|Group|Graphic Editor|
|Descr.|Calculates the exposed area of a layer/s; the operation is performed on the raster image of the layer using a user-defined mask layer. The distribution map and the thermal map are created for the user interface popup and cannot be accessed with this command.|
|Response|Contains the total exposed value + the copper percentage.<br>Syntax: ccccc ppppp (ccccc - exposed area, ppppp - percentage).


|----|----|
|Parameter| Value|
|layer1| Existing layer name|
|mask1| Layer1’s mask layer|
|layer2| Existing layer name|
|mask2| Layer2’s mask layer, needed only when layer2 is defined|
|drills| Yes - considers drill layers<br>No - no drill layers|
|drills_<br>source|Matrix - take from Job Matrix<br>Manual - take list of drills|
|resolution| 1/4, 1/2, 1 mils to define precision of rasterization calculation|
|thickness| 0 <= thickness (depth of drills, used to calculate drill barrel area)|
|x_boxes,<br>y_boxes|1 <= num <= 200 to define number of boxes (of copper distribution) in X,Y axes|
|area| Yes - use specified area (x1, y1, x2, y2)<br>No - copper area for whole layer|
|x1, y1,<br>x2, y2|Legal coordinates to define rectangular area corners|
|dist_map| Yes - create distribution map<br>No - no distribution map|
|f_type| All - all features are selected<br>Selected - only selected features.|
|out_file| Output file (optional)|
|out_layer| First/second/sum - what layer to display in out_file.|
|consider_<br>rout|Yes: rout features are considered when calculating the copper area.<br>No: rout features are not considered when calculating the copper area.<br>Note: This feature is implemented only if the parameter drill=yes in either line mode command copper_area or exposed_area.
|edges| Values = [no/yes] (default = no). If yes, consider copper edges when calculating total copper area in a layer.|

|----|----|
|Parameter| Value|
|consider<br>_thickness|Thickness of copper edge areas. Values = [0..Max Coordinate] in mil/my. Useful only when edges=yes.|
|multi_mask<br>_mode|Defines how to consider two or more mask layers used to define exposed areas.<br>Values:<br>or (default) = Use area covered by at list one mask.<br>and = Use only area covered by all masks.|




<h2 id="ezcam_get_uid">ezcam_get_uid</h2>

無

|----|----|

<h2 id="ezcam_semiauto_dimension_show">ezcam_semiauto_dimension_show</h2>

|----|----|

無

<h2 id="ezcam_test_assert">ezcam_test_assert</h2>
無
<h2 id="ezcam_test_end">ezcam_test_end</h2>
無
<h2 id="ezcam_test_fail">ezcam_test_fail</h2>
無
<h2 id="ezcam_test_msg">ezcam_test_msg</h2>
無
<h2 id="ezcam_test_start">ezcam_test_start</h2>
無
<h2 id="feat_hist_close">feat_hist_close</h2>

|----|----|
|Command| feat_hist_close|
|Group|Graphic Editor|
|Description|The feat_hist_close command closes the layer features histogram.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|
|type|features-features histogram<br>slots - slot features histogram (drill layer only)<br>sr - features histogram (+S&R)

<h2 id="feat_hist_open">feat_hist_open</h2>

|----|----|
|Command| feat_hist_open|
|Group| Graphic Editor|
|Description|The feat_hist_open command opens the Layer Features histogram.|

|----|----|
|Parameter|Value|
|layer| Existing layer name|
|type| features - features histogram<br>slots - slot features histogram (drill layer only)<br>sr - features histogram (+S&R)


<h2 id="fill_params">fill_params</h2>

|----|----|
|Command| fill_params|
|Group| Graphic Editor|
|Descr.|Sets the contour fill parameters, that are used by all the commands that require the filling function (the command does not perform any filling!!!).|

|----|----|
|Parameter| Value|
|type| Solid - full copper fill<br>Pattern - fill with symbol|
|origin_<br>type|Datum - step datum<br>Limits - lower left corner of the specified area|
|solid_<br>type|Surface - create a surface feature - Relevant if type = solid<br>Fill - vectoric fill|
|min_brush| 0 < size < max size - Relevant if solid_type = fill|
|use_acrs| Yes - Use arcs in fill<br>No - do not use arcs in fill<br>(Relevant if solid_type ==fill|
|symbol| Entity name - Relevant if type = ‘pattern’|
|dx, dy| Fill pattern step 0 < size < max_size - Relevant if type =‘pattern’
|break_<br>partial|Yes - break partial special symbols - Relevant if type = ‘pattern’<br>No - if the special symbol is not fully contained in the contour - don’t add it!!!|
|cut_prims| Yes - polygon cut of symbols that intersect with the fill contour - relevant if type = pattern<br>No - intersecting features are eliminated
|outline_<br>draw| Yes - outline is drawn around the islands and holes<br>No - no outline
|outline_<br>width|0 <= width <= max_size - relevant if outline_draw = ‘yes’|
|outline_<br>invert|Yes - invert the polarity of the outline - relevant if outline_draw = ‘yes’<br>No - use the same polarity as the pattern



<h2 id="filter_area_end">filter_area_end</h2>

|----|----|
|Command| filter_area_end|
|Group|Graphic Editor|
|Descr.|Used for selecting features in all of the affected layers according to the features filter,and to a specified polygon/rectangle area.|

|----|----|
|Parameter| Value|
|layer| If empty string all the affected layers are taken|
|filter_name| Entity name - as specified in the ‘filter_set’ command|
|operation| Select, unselect|
|area_type| None - no area filter<br>Rectangle - x1,y1,x2,y2 specify the rect corners<br>Polygon -up to 50 points|
|inside_area| Yes - features inside if area_type!=None <br>No - outside the area|
|intersect_area|Yes - takes features that ALSO intersect the area - if area_type!=None<br>No - only features that are inside/outside the area|
|lines_only| If yes => allow only lines in a certain length and angle limit to pass filter - no = default.|
|oval_only| If yes => allow only oval pads in a certain length and angle limit to pass filter - no = default.|
|min_len,<br>max_len|Length limits (inch/mm) - used only if in lines_only mode max val = 250 inch|
|min_angle,<br>max_angle|Angle limits (degree) - used only if in “XXXX_only” mode|


<h2 id="filter_area_strt">filter_area_strt</h2>

|----|----|
|Command| filter_area_strt|
|Group|Graphic Editor|
|Descr.|Command for starting an area selection (it resets the points list).|

<h2 id="filter_area_xy">filter_area_xy</h2>

|----|----|
|Command| filter_area_xy|
|Group|Graphic Editor|
|Descr.|Command for adding a polygon/rectangle point.

|----|----|
|Parameter| Value|
|x, y| legal x,y coordinates|




<h2 id="filter_atr_reset">filter_atr_reset</h2>

|----|----|
|Command| filter_atr_reset|
|Group|Graphic Editor|
|Descr.|Resets the attributes filter (clears it!!!).|

|----|----|
|Parameter| Value|
|filter_<br>name|Entity name - required by the commands that use the filter params|

<h2 id="filter_atr_set">filter_atr_set</h2>

|----|----|
|Command| filter_atr_set|
|Group|Graphic Editor|
|Descr.|Sets the attributes filter parameters. These parameters are used as part of the upper level features filter (set by the command - filter_set).|

|----|----|
|Parameter| Value|
|filter_<br>name|Entity name - required by the commands that use the filter params|
|attribute| Entity name - attribute name|
|condition| Yes - filter also by the feature attribute value<br>No - filter only according to the attribute name|
|text| Free text - used for text attributes|
|option| Valid option value - used for option (based on the attribute attributes definition)|
|min_int<br>_val|Valid integer value - used for integer attributes (minimal value)
|max_float<br>_val|Valid	 float value - used for float attributes (maximal value)|
|min_float<br>_val|Valid float value - used for float attributes (minimal value)|

<h2 id="filter_highlight">filter_highlight</h2>

|----|----|
|Command| filter_highlight|
|Group|Graphic Editor|
|Descr.|Used for highlighting features according to a specified filter|


|----|----|
|Parameter| Value|
|layer| If empty string - all the affected layers are taken|
|filter_<br>name|Entity name - as specified in the filter_set command|
|lines_<br>only|If yes => allow only lines in a certain length and angle limit to pass filter - no = default.|
|ovals_<br>only|If yes => allow only oval pads in a certain length and angle limit to pass filter - no =default.|
|min_len,<br>max_len|Length limits (inch/mm) - used only if in XXXXX_only mode - max value = 250 inch|
|min_angle<br>max_angle|Angle limits (degrees) - used only if in XXXXX_only|



<h2 id="filter_reset">filter_reset</h2>

|----|----|
|Command| filter_reset|
|Group|Graphic Editor|
|Descr.|Resets all the filter values to their default values|

|----|----|
|Parameter| Value|
|filter_<br>name|Entity name - required by the commands that use the filter params|



<h2 id="filter_set">filter_set</h2>

|----|----|
|Command |filter_set|
|Group|Graphic Editor|
|Descr.|The command is used for setting the features filter parameters. The filter is used for various functions, such as ‘features selection’.|


|----|----|
|Parameter| Value|
|filter_name| Entity name - required by the @Commands that use the filter params|
|update_popup| Yes - update the ui popup according to the new values<br>No - no update|
|active| Yes - the filter is active <br> No - the filter becomes inactive (all the following params are not relevant)
|feat_types| - line<br>- pad<br>- surface<br>- arc<br>- text - set field|
|polarity| - positive -<br>- negative - set field
|include_syms| Wild symbol names separated by ‘;’ characters - symbol names to be included|
|exclude_syms| Wild symbol - names separated by ‘;’ characters - symbol names to be excluded|
-------------
Ranges for Symbol Names
You can define a range of Genesis symbols for use in selected Genesis filters, line mode commands, and popups. Two standard or semi-standard symbol names of the
same type separated by a colon (:) define the range of symbols. All existing Genesis symbol types may be included in the list.
Any symbol filter may be defined as a list of symbol definition names separated by a semicolon (;). Symbol definition names may be written using any of the following
rules:


- Any legal symbol name.
- Wild card name (a name with an asterisk mark (*).
Examples: "s*" or "rect100x*" or "rect*x50" .
- Note: The symbol definition name * (used by itself) means no filter. (All symbol
names are ignored.)

**r100:r300:** matches all round symbols between 100 (inclusive) and 300
(inclusive). It matches r100 , r100.1 , r150.34 , r300, but does not match
r99.99 or r300.1.


**rect20x30:** rect100x50 matches all rectangle symbols where the width is
between 20 and 100 and the length is between 30 and 50. It therefore matches
rect20x40, rect100x50, and rect20.123x99.999, but does not match
rect20x100.1
Also applicable to Reference Selection Popup and Features Filter Popup. See Doc. 0601, The Graphic Editor, for more information.

---------

|----|----|
|profile| All - ignore the profile<br>In - inside the profile<br>Out - outside the profile
|dcode| -1 for all or dcode number can also be used for drill tool numbers|
|text| Any valid string|
|slot| line and/or oval (Default=None)<br>line - line slots should be filtered<br>oval - oval slots should be filtered
|slot_by| length and/or angle (Default = [length and angle]) <br> length - line and/or oval should be filtered by length<br>angle - line and/or oval should be filtered by angle|
|min_len,<br>max_len|length limits (inch/mm).<br> Parameters are only used if slot = line or/and<br>oval and slot_by = length.|
|min_angle,<br>max_angle|Single limits in range [-180º .. +180º] degrees (clockwise rotation).<br>Parameters are<br>only used if slot = line or/and oval and slot_by = angle.|

<h2 id="flatten_layer">flatten_layer</h2>

|----|----|
|Command| flatten_layer|
|Group|Graphic Editor|
|Descr.|The command receives as input a layer that contains step & repeat data, and it flattens it, and creates a new layer that contains the broken step & repeat features.|
|Response|Contains the total copper value + the copper percentage.<br>Syntax: ccccc ppppp (ccccc - copper area, ppppp - percentage).|


|----|----|
|Parameter| Value|
|source_<br>layer|Existing layer name|
|target_<br>layer|Layer to create|

<h2 id="flip_step">flip_step</h2>

|----|----|
|Command| flip_step|
|Group|Panelization Package|
|Descr.| The command allows you to create a new step which is a flipped copy of asource step.|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Name of existing step in the job to be flipped|
|new_step| Name of a new (flipped) step|
|new_layer_<br>suffix|Suffix to be added to the name of layer created during the flipping procedure|
|mode| flipping mode, defines the mirroring of the layer features as being relative to either the<br>**axis**(relative to line X=0)<br>**center** (relative to line X = the middle point of the profile).







<h2 id="form_elem_visibility">form_elem_visibility</h2>

|----|----|
|Command| form_elem_visibility|
|Group|Work Forms|
|Descr.|Sets the specified element as enabled/disabled. This command affects only the current view of the form, and does not change the form definition in the database.|

|----|----|
|Parameter| Value|
|job| Name of the job|
|form| Name of form|
|elem| Name of element|
|mode| Sensitive, unsensitive, hide, unhide|





<h2 id="get_affect_layer">get_affect_layer</h2>

|----|----|
|Command| get_affect_layer|
|Group|Graphic Editor|
|Descr.|The command is used for getting the names of the affected layers.|
|Response|layer1, layer2......layern|


<h2 id="get_disp_layers">get_disp_layers</h2>

|----|----|
|Command| get_disp_layers|
|Group|Graphic Editor|
|Description|The get_disp_layers command is used to get the names of the currently displayed layers.|
|Response|layer1 layer2......layern|



<h2 id="get_select_count">get_select_count</h2>

|----|----|
|Command| get_select_count|
|Group|Graphic Editor|
|Descr.|The command is used for getting the number of selected features.|
|Response|nnnnn - number of selected features|


<h2 id="get_units">get_units</h2>

|----|----|
|Command| get_units|
|Group|Graphic Editor|
|Descr.|Gets the current units.|
|Response|Inch/mm|



<h2 id="get_user_name">get_user_name</h2>
|----|----|
|Command| get_user_name|
|Group|Engineering Toolkit|
|Descr.|The command returns the user name that is currently logged into the system.|
|Response| user_name|


<h2 id="get_version">get_version</h2>

|----|----|
|Command| get_version|
|Group|Engineering Toolkit|
|Descr.|The command returns the version number that is currently logged into the system.|
|Response| version|

<h2 id="get_work_layer">get_work_layer</h2>

|----|----|
|Command| get_work_layer|
|Group|Graphic Editor|
|Descr.|The command is used for getting the name of the work layer.|
|Response| work_layer (or empty string if there is no work layer)|



<h2 id="import_job">import_job</h2>

|----|----|
|Command| import_job|
|Group|Engineering Toolkit|
|Descr.|Performs automatic import of Genesis 2000 job that was previously exported|

|----|----|
|Parameter| Value|
|db| Genesis 2000 job database to which the job will be imported|
|path| file path of imported job|
|name| name of job in database after import|
|analyze_<br>surfaces|Yes or No. If yes run the Surface Analyzer after importing.|



<h2 id="info">info</h2>

|----|----|
|Command| info|
|Group|Engineering Toolkit|
|Descr.|Used for getting database information


|----|----|
|Parameter| Value|
|args| Legal arguments string - will be described for the output information|
|out_file| Legal file pathname - will be described for the output information|
|write_mode| Replace - replace existing file append - to the end of an existing file|
|units| Inch, mm - output units<br><br>**Note:**     For more details see Scripts (Doc 0204).<br>The y2k_info_4 configuration parameter determines the use of 4-digit year format.|


<h2 id="input_auto">input_auto</h2>

|----|----|
|Command| input_auto|
|Group|Engineering Toolkit|
|Descr.|The command performs a full automatic input translation. A full detailed report is created, and there is an option to copy the input directory to the job directory in the database.<br>The command does not update the input screen.


|----|----|
|Parameter| Value|
|path| Input directory/file path|
|job| Existing job name|
|step|	 Existing step name for layer formats|
|report_<br>path|Legal file pathname|
|copy_to_<br>job|Yes - at the end of the operation the input dir is copied to the job dir<br>No -
|no copy||
|ident_<br>script_<br>path|Identification script path|
|trans_br>script_br>path|Translation script path|



<h2 id="input_copy">input_copy</h2>

|----|----|
|Command| input_copy|
|Group|Engineering Toolkit|
|Descr.|Used for copying the original input dir to the job dir. The command does not update the input screen.|

|----|----|
|Parameter| Value|
|path| Existing input directory|
|job| Existing job name - target job|
|delete_<br>source|Yes - delete the source dir<br>No - only copy|


<h2 id="input_cur_report">input_cur_report</h2>

|----|----|
|Command| input_cur_report|
|Group|Engineering Toolkit|
|Descr.|The command is used for placing the current input session report into a file.|

|----|----|
|Parameter| Value|
|path|Report path|


<h2 id="input_dcodes_add">input_dcodes_add</h2>
 

|----|----|
|Command| input_dcodes_add|
|Group|Engineering Toolkit|
|Descr.|The command is used for adding a gerber file pathname to the files list. This list is used by the input_dcodes_get command to get all the used dcodes.|

|----|----|
|Parameter| Value|
|path| Gerber file path|
|data_type| ASCII, EBCDIC, binary|
|units| Inches, mm|
|coordinates| Absolute, incremental|
|zeroes| None, leading, trailing|
|decimal| Yes - decimal point (nf, nf2, is not required)<br>No - no decimal point (nf1 and nf2 are required)
|nf1, nf2| 1<=nf1, nf2<=6|
|separator| ‘*’,’$’, ‘#’, NL (new line)|





<h2 id="input_dcodes_get">input_dcodes_get</h2>

|----|----|
|Command| input_dcodes_get|
|Group|Engineering Toolkit|
|Descr.|The command uses the Gerber files list, that was created by calling the input_dcodes_reset and input_dcodes_add commands, to get a list of all the used dcodes. The list is placed in an ASCII file that contains a number per line. Each number is a dcode number. Even if the list is empty the file will be created.|

|----|----|
|Parameter| Value|
|report_<br>path||



<h2 id="input_dcodes_match">input_dcodes_match</h2>

|----|----|
|Command| input_dcodes_match|
|Group|Engineering Toolkit|
|Descr.|The command is used for comparing a specified job wheel with a dcodes list that was created by the input_dcodes_get command. It create a new file that contains the dcodes in the input file that don’t have matching dcodes in the wheel. The output file contains a csh style array named - gUDCODES. The file can be ‘sourced’ in a **csh**script.|


|----|----|
|Parameter| Value|
|job| Job name|
|wheel| Wheel name|
|inp_<br>dcodes_<br>list|Created by the input_dcodes_get command|
|script_<br>path|Output script path|




<h2 id="input_dcodes_reset">input_dcodes_reset</h2>


|----|----|
|Command| input_dcodes_reset|
|Group|Engineering Toolkit|
|Descr.|Used for resetting the Gerber files list that is used by the input_dcodes_get command to get all the used dcodes of a specified Gerber files list.|



<h2 id="input_extract_hdr">input_extract_hdr</h2>

|----|----|
|Command| input_extract_hdr|
|Group|Engineering Toolkit|
|Descr.|Used for extracting the header sections for gerber, and excellon files. This is important for files that contain the dcode tables as well as the standard data. The command does not update the input screen.|
|Response|‘Yes, No’ indicator whether a header was extracted or not.|

|----|----|
|Parameter| Value|
|format| Gerber, Pentax, Excellon1, Excellon2|
|file_path| Gerber/ Excellon file|
|out_path| Extracted file path|
|separator| Gerber file separator|





<h2 id="input_hide_page">input_hide_page</h2>


|----|----|
|Command| input_hide_page|
|Group|Engineering Toolkit|
|Descr.|Hides the input page|




<h2 id="input_identify">input_identify</h2>

|----|----|
|Command| input_identify|
|Group|Engineering Toolkit|
|Descr.|Performs an input identification to the specified input pathname. It creates a summary file in a‘csh’ script format, that can be sourced. The command does not update the input screen.|

|----|----|
|Parameter| Value|
|path| Input directory / file path|
|job| Existing job name|
|script_<br>path|Legal file pathname for output summary<br>Note: The parameter giERROR was added to the output summary file found in the script_path of the input_identify line mode command). The parameter takes the value of the error massage if Genesis selects a wheel template with errors (e.g.unassigned dcodes), or is an empty string if there are no errors in the selected wheel template.|
|unify| Yes to perform unification as part of identification|
|break_sr| Yes to break step & repeat|
|gbr_ext| Yes to extract wheel for Gerber file automatically|
|drl_ext| Yes to extract wheel for drill file automatically|
|gbr_units| Inch, mm, auto - units during Gerber file identification|
|drl_units| Inch, mm, auto - units during drill file identification|
|bgr_wtp_<br>units|Inch, mm, auto - (Gerber). This parameter is used to filter out wheel templates with units of measurement that don't match the units specified by the line mode command. If the parameter is omitted, the default is auto. Example: If the value is Inch, then all the mm wheel templates are filtered out and are not used as candidates.|
|drl_wtp_<br>units|Inch, mm, auto - (tool wheel). This parameter is used to filter out wheel templates with units of measurement that don't match the units specified by the line mode command. If the parameter is omitted, the default is auto. Example: If the value is Inch, then all the mm wheel templates are filtered out and are not used as candidates.|
|drl_wtp_<br>filter|list of wild card expressions for drill wtp|
|drl_wtp_<br>units|inch/mm/auto - drill wtp units during identification|
|drl_wtp_<br>filter|(tool wheel) This parameter is a wild card expressions used to filter out wheel templates by name. If the parameter is omitted, the default is * .|
|gbr_wtp_<br>filter|list of wild card expressions for gerber wtp|
|gbr_wtp_<br>filter|(Gerber) This parameter is a wild card expressions used to filter out wheel templates by name. If the parameter is omitted, the default is * .|
|gbr_wtp_<br>units|inch/mm/auto - gerber wtp units during identification|
|wtp_dir| Legal directory pathname for using wheel templates.<br>(Default): Tells Genesis to use original wheel templates.<br>dir_path: Specifies path to alternate wheel templates.<br>**Note:** The directory contained in this parameter must contain the 'whltemps' library.<br>This library should contain wheel templates. The parameter forces Genesis to use the wheel templates in this directory instead of wheel templates from the original wheel template directory.






<h2 id="input_manual">input_manual</h2>

|----|----|
|Command| input_manual|
|Group|Engineering Toolkit|
|Descr.|The command executes a manual input operation for the files that were specified in the input_manual_set command.<br>The command does not update the input screen.|

|----|----|
|Parameter| Value|
|script_<br>path|Output ‘csh’ script report path.|





<h2 id="input_manual_reset">input_manual_reset</h2>

|----|----|
|Command| input_manual_reset|
|Group|Engineering Toolkit|
|Descr.|The command resets the input files list that is used by the input_manual command.The command does not update the input screen.|



<h2 id="input_manual_set">input_manual_set</h2>

|----|----|
|Command| input_manual_set|
|Group|Engineering Toolkit|
|Descr.|The command adds an external file to the input list. Each entry includes the file path and all the required parameters. Multiple calls to this command creates a list that is used by the ‘input_manual’ command. This command does not perform any translations!!!! The command does not update the input screen.|

|----|----|
|Parameter| Value|
|path| Existing file/dir pathname - input path|
|job| Existing job name - target job|
|step| Existing step name - target step (for layer formats)|
|format| Gerber, Gerber274x, Auto-plot image,Par, Excellon1, Excellon2, DFX, Mentor|
|data_type| ASCII, EBCDIC, EIA, binary -for all gerbers and execllon|
|units| Inch, mm|
|coordinates| Absolute, incremental|
|zeroes| None, leading, trailing|
|decimal| Yes - decimal point (nf1,nf2 is not required)<br> No - no decimal point (nf1, and nf2 are required)
|nf1, nf2| Number format (1 <=n <=6)|
|nf_comp| 0 - Only read Netlist<br>1 - Also read Components<br>- for Mentor Neutral files|
|separator| ‘*’, ‘$’, ‘#’, NL (new line)|
|tool_units| Inch, mm - for drill formats|
|signed_<br>coords|Yes<br>No - for Wessel Files|
|layer| Entity name - target layer (for layer formats)|
|wheel| Existing wheel name for gerber format|
|wheel_<br>template|Existing wheel template or empty string|
|multiplier| 0.000001<=x ,= 1000000.0 - for DXF files|
|break_sr| True if break s&r|



<h2 id="input_set_params">input_set_params</h2>

|----|----|
|Command| input_set_params|
|Group|The Input Process|
|Descr.|The command completes all the fields at the input screen. No identification or translation is performed.|

|----|----|
|Parameters| Value|
|path| Input directory / file path|
|job| Existing job name|
|step| Existing step name - for layer formats|
|exclude| Files to include - file filter|
|wheels| Yes /No|
|gbr_template| Text|
|gbr_<br>headlines|Yes / No|
|name| Text|
|tool_<br>template|Text|
|tool<br>headlines|Yes / No|
|gbr_ext| Yes to extract wheel for gbr file automatically|
|gbr_units| Inch/mm/auto - units during gerber files identification|
|drl_ext| Yes to extract wheel for drill file automatically|
|drl_units| Inch/mm/auto - units during drill files identification|
|force| Yes / No - Forces the screen to be overwritten|



<h2 id="input_show_page">input_show_page</h2>


|----|----|
|Command| input_show_page|
|Group|Engineering Toolkit|
|Descr.|The command shows the input page.|


<h2 id="invert_feat">invert_feat</h2>

|----|----|
|Command| invert_feat|
|Group|Graphic Editor|
|Descr.|Inverts the polarity of a feature in all the affected layers|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|tol| 0 <= tol (mils) - snap tolerance|


<h2 id="matrix_add_col">matrix_add_col</h2>

|----|----|
|Command| matrix_add_col|
|Group|Engineering Toolkit|
|Descr.|The command adds a new column at the end of a matrix.|


|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|


<h2 id="matrix_add_layer">matrix_add_layer</h2>

|----|----|
|Command|matrix_add_layer|
|Group|Engineering Toolkit|
|Descr.|The command adds a new layer to the job matrix. The layer is created in all of the job steps.|
|Response|None|



|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Entity name|
|row| Existing empty row|
|context| Board, misc|
    type
    - signal
    - power_ground
    - mixed
    - solder_mask
    - silk_screen
    - solder_paste
    - drill
    - rout
    - document

| polarity| Positive, negative |
| :--- | :----: |







<h2 id="matrix_add_row">matrix_add_row</h2>


|----|----|
|Command| matrix_add_row|
|Group|Engineering Toolkit|
|Descr.|The command adds a new row at the end of a matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|





<h2 id="matrix_add_step">matrix_add_step</h2>

|----|----|
|Command| matrix_add_step|
|Group|Engineering Toolkit|
|Descr.|The command adds a new step to the matrix. The specified target column must exist,and be empty.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|step| Entity name|
|col| Existing empty column|




<h2 id="matrix_auto_rows">matrix_auto_rows</h2>


|----|----|
|Command| matrix_auto_rows|
|Group|Engineering Toolkit|
|Descr.|The routine is used for automatically re-arranging the rows according to the layer naming convention, as it is defined in the lyr_rule file.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|




<h2 id="matrix_copy_col">matrix_copy_col</h2>

|----|----|
|Command| matrix_copy_col|
|Group| Engineering Toolkit|
|Descr.| The command copies a column in a job matrix. If the column contains a step name, the step data will be copied as well.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|col| Exiting column|
|ins_col| 1 <= ins_col - target location|


<h2 id="matrix_copy_row">matrix_copy_row</h2>

|----|----|
|Command| matrix_copy_row|
|Group|Engineering Toolkit|
|Descr.|The command copies a row in a job matrix. If the row contains a layer name, the layer data of all the job steps will be copied as well.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|row| Exiting row|
|ins_row| 1 <= ins_row - target location|




<h2 id="matrix_delete_col">matrix_delete_col</h2>

|----|----|
|Command| matrix_delete_col|
|Group|Engineering Toolkit|
|Descr.|The command deletes a column from a job matrix. If the column contains a step name, the step will be removed from the job.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|col| Existing column|


<h2 id="matrix_delete_row">matrix_delete_row</h2>


|----|----|
|Command|matrix_delete_row|
|Group|Engineering Toolkit|
|Descr.|The command deletes a row from a matrix. If the row contains a layer name, the layer will be deleted from all the steps that are part of the job.|


|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|row| Existing row|




<h2 id="matrix_dup_col">matrix_dup_col</h2>

|----|----|
|Command| matrix_dup_col|
|Group|Engineering Toolkit|
|Descr.|The command duplicates a column in the job matrix, and places the new column after the input one. If the column contains a step name, the step entity will also be duplicated.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|col| Exiting column|



<h2 id="matrix_dup_row">matrix_dup_row</h2>

|----|----|
|Command| matrix_dup_row|
|Group|Engineering Toolkit|
|Descr.|The command duplicates a row in the job matrix, and places the new row after the input one. If the row contains a layer name, then the layers data in all the job steps will be duplicated as well.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|row| Exiting row|



<h2 id="matrix_insert_col">matrix_insert_col</h2>

|----|----|
|Command| matrix_insert_col|
|Group|Engineering Toolkit|
|Descr.|The command inserts a new column in a matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|col| 1 <= col|


<h2 id="matrix_insert_row">matrix_insert_row</h2>

|----|----|
|Command| matrix_insert_row|
|Group|Engineering Toolkit|
|Descr.|The command inserts a new row in a matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix |Existing matrix name|
|row| 1 <= row|



<h2 id="matrix_layer_context">matrix_layer_context</h2>

|----|----|
|Command| matrix_layer_context|
|Group|Engineering Toolkit|
|Descr.|The command sets the layer context in the job matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Existing layer name|
|context| Board, misc|



<h2 id="matrix_layer_drill">matrix_layer_drill</h2>

|----|----|
|Command| matrix_layer_drill|
|Group|Engineering Toolkit|
|Descr.|The command defines the start and end layers of a drill layer. If the drill layers contains only through holes, the specified layer names may be empty strings.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Existing drill layer name|
|start| Existing layer name|
|end |Existing layer name|




<h2 id="matrix_layer_polar">matrix_layer_polar</h2>

|----|----|
|Command| matrix_layer_polar|
|Group|Engineering Toolkit|
|Descr.|The command sets the layer polarity in the job matrix.|

|----|----|
|Parameter |Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Existing layer name|
|polarity| Positive, negative|




<h2 id="matrix_layer_type">matrix_layer_type</h2>

|----|----|
|Command| matrix_layer_type|
|Group|Engineering Toolkit|
|Descr.|The command sets the layer type in the job matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Existing layer name|
    type : 
    - signal
    - power_ground,
    - mixed,
    - solder_mask,
    - silk_screen,
    - solder_paste
    - drill
    - rout
    - document
    



<h2 id="matrix_move_col">matrix_move_col</h2>

|----|----|
|Command| matrix_move_col|
|Group|Engineering Toolkit|
|Descr.|The command moves a column to a new location in a job matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|col| Exiting column|
|ins_col| 1 <= ins_col - new location|



<h2 id="matrix_move_row">matrix_move_row</h2>

|----|----|
|Command| matrix_move_row|
|Group|Engineering Toolkit|
|Descr.|The command moves a row to a new location in a job matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|row| Exiting row|
|ins_row| 1 <= ins_row - new location|



<h2 id="matrix_page_close">matrix_page_close</h2>

|----|----|
|Command| matrix_page_close|
|Group|Engineering Toolkit|
|Descr.|The routine is used for closing a matrix page.|

|----|----|
|Parameter| Value|
|job| name of an existing opened job|
|matrix| existing matrix name|



<h2 id="matrix_refresh">matrix_refresh</h2>

|----|----|
|Command| matrix_refresh|
|Group|Engineering Toolkit|
|Descr.|Refreshes the display of a matrix popup.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|




<h2 id="matrix_rename_layer">matrix_rename_layer</h2>

|----|----|
|Command| matrix_rename_layer|
|Group|Engineering Toolkit|
|Descr.|The command renames a layer in the matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|layer| Existing layer name|
|new_name| Entity name|




<h2 id="matrix_rename_step">matrix_rename_step</h2>

|----|----|
|Command| matrix_rename_step|
|Group|Engineering Toolkit|
|Descr.|The command renames a step entry (column) in a job matrix.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|matrix| Existing matrix name|
|step| Existing step name|
|new_name| Entity name|


<h2 id="mirror_feat">mirror_feat</h2>



|----|----|
|Command| mirror_feat|
|Group|Graphic Editor|
|Descr.|Mirrors a feature around it’s axis point (in X axis).|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.| 
|x, y|Legal coordinates - feature coordinates|
|tol| 0 <= tol (mils) - snap tolerance|

<h2 id="move_corner">move_corner</h2>

|----|----|
|Command| move_corner|
|Group|Graphic Editor|
|Descr.|Moves a contour corner (vertex).|

|----|----|
|Parameter| Value|
|x, y |Legal coordinates (inches/mm) - corner coordinates before movement.|
|new_x,<br>new_y|Legal coordinates (inches/mm) - new corner coordinates.|


<h2 id="move_feat">move_feat</h2>


|----|----|
|Command| move_feat|
|Group|Graphic Editor|
|Descr.|Moves a feature in all the affected layers.|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|dx, dy| Legal coordinates - shift values|
|tol| 0 <= tol (mils) - snap tolerance|


<h2 id="move_hole">move_hole</h2>


|----|----|
|Command| move_hole|
|Group|Graphic Editor|
|Descr.|Moves a contour hole (must be a hole with no inner islands).|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates (inch/mm) - coordinates of a point within the hole to be moved|
|dx, dy| Legal coordinates (inch/mm) - shift values|


<h2 id="move_job">move_job</h2>

|----|----|
|Command| move_job|
|Group| Engineering Toolkit|
|Descr.| Used to move a job from one database to another.|

|----|----|
|Parameter| Value|
|source_job| existing job name. may contain wildcard|
|dest_job| destination job name. Can be same as source_job|
|dest_database| destination database to move the job|


<h2 id="move_junction">move_junction</h2>
|----|----|
|Command| move_junction|
|Group|Graphic Editor|
|Descr.|The line mode command mechanism use either lines indexes (IND1, IND2) or old junction coordinates (XJUNC, YJUNC) to select the junction to be moved.<br>If you wish to use the first method - set line indexes only, XJUNC and YJUNC do not need to be set.Otherwise set both line indexes to 1 and place the old junction coordinates (x,y) in(XJUNC, YJUNC).|

|----|----|
|Parameter| Value|
|index1=**<IND1**><br>index2=**<IND2**>|Line-feature index in the work layer<br>IND1, IND2 - junction line indexes|
|x=**<XJUNC**><br>y= **<YJUNC**>|Legal coordinates - coordinates XJUNC,YJUNC = old position of junction|
|new_x**<NEWX**><br>new_y**<NEWY**>|Legal coordinates - coordinates NEWX, NEWY = new position of junction

**Note: When you are in immediate online net mode you cannot perform the
command move_junction.**


<h2 id="move_triplet">move_triplet</h2>

|----|----|
|Command| move_triplet|
|Group|Graphic Editor|
|Descr.|Moves a line triplet|

|----|----|
|Parameter| Value|
|indexes(start,<br>middle,<br>end)|Triplet lines indexes in the work layer|
|shift| Legal coordinate - middle line shift|
|direction| Positive - movement is in positive Y-Axis direction, or if middle line is vertical, positive<br>X-Axis direction<br>Negative -|
|mode| fixed_length; fixed_angle - Triplet movement mode|



<h2 id="move_triplets">move_triplets</h2>

|----|----|
|Command| move_triplets|
|Group|Graphic Editor|
|Descr.|Moves a group of line triplets.<br>Comment: Selected triplets’ mid-lines should be of approximately the same angle|


|----|----|
|Parameter| Value|
|shift| Positive value, triplet shift (inch/mm)|
|direction| Positive - movement is in positive Y-Axis direction, or if middle line is vertical, positive<br>X-Axis direction<br>Negative -|
|mode| FIX_ANGLE / FIX_LENGTH|



<h2 id="ncd_cre_drill">ncd_cre_drill</h2>

|----|----|
|Command| ncd_cre_drill|
|Group|Auto Drill Manager|
|Descr.|The command creates the drill and NC files.|


<h2 id="ncd_ncf_export">ncd_ncf_export</h2>

|----|----|
|Command| ncd_ncf_export|
|Group|Auto Drill Manager|
|Descr.|The command is used for exporting the drill file from the NC-set.|

|----|----|
|Parameter| Value|
|stage| Drill stage (1, 2, 3)|
|split| Split number (1, 2)|
|dir| Directory path|
|name| File name|



<h2 id="ncd_register">ncd_register</h2>

|----|----|
|Command| ncd_register|
|Group|Auto Drill Manager|
|Descr.|The command is used for setting the registration values.|

|----|----|
|Parameter| Value|
|angle| 0, 90, 180, 270|
|mirror| Yes, No|
|xoff, yoff| Offset values|
|version| 1 - 8 - coordinates version|
|xorigin,<br>yorigin,|
|xscale,<br>yscale|Scale factor (def = 1.0) 0.95 >= factor <= 1.05
|xscale_o,<br>yscale_o|Scale anchor coordinates relative to the STEP



<h2 id="ncd_set_machine">ncd_set_machine</h2>

|----|----|
|Command| ncd_set_machine|
|Group|Auto Drill Manager|
|Descr.|Used for setting the drill machine name, and some other parameters.|

|----|----|
|Parameter| Value|
|machine| Existing machine name|
|thickness|



<h2 id="ncd_table_set">ncd_table_set</h2>

|----|----|
|Command| ncd_table_reset|
|Group|Auto Drill Manager|
|Descr.|The command is used for resetting a temporary nc-table, that is set by the ncd_table_set command.|


<h2 id="ncset_cur">ncset_cur</h2>

|----|----|
|Command| ncset_cur|
|Group|Auto Drill Manager|
|Descr.|The command is used for setting the** CURRENT** entity name that are used for all the other line mode commands.|


|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|layer| Existing layer name|
|ncset| Existing ncset name|



<h2 id="ncset_units">ncset_units</h2>

|----|----|
|Command| ncset_units|
|Group|Auto Drill Manager|
|Descr.|The command is used for setting the CURRENT working units.|

|----|----|
|Parameter| Value|
|units| inch, mm|




<h2 id="netlist2layer">netlist2layer</h2>

|----|----|
|Command| netlist2layer|
|Group|Graphic Editor|
|Descr.|The command is used for creation of a graphic layer with points corresponding each test point in net. Such layer may be used as drill layer for test plates creation|
|Response|The number of created layers|


|----|----|
|Parameter| Value|
|netlist| CAD, refnet, current, curcad|
|staggered| Yes, No|
|finished| Yes, No|
|optimized| Yes, No|
|comment| Yes, No|
|hole_size| Size in units - Default hole size
|top_layer| Layer name
|bot_layer| Layer name
|through_<br>layer|Layer name|
|inner_layer<br>_prefix|Prefix for inner layer names|




<h2 id="netlist_auto_reg">netlist_auto_reg</h2>

|----|----|
|Command| netlist_auto_reg|
|Group|Engineering Toolkit|
|Descr.|The command registers the CAD netlist of a step (if exists) with the rest of the step automatically. The automatic registration is attempted vs. the drill layer and the outer layers.|
|Response|1 if succeeded, 0 if failed|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|




<h2 id="netlist_compare">netlist_compare</h2>

|----|----|
|Command| netlist_compare|
|Group|Engineering Toolkit|
|Descr.|The command displays the netlist analyzer window and optionally sets the job/step/type values of the window|

|----|----|
|Parameter| Value|
|job1| Existing job name|
|step1| Existing step name|
|type1| CAD, refnet, current, curcad|
|job2|Existing job name|
|step2| Existing step name|
|type2| CAD, refnet, current, curcad|
|display| None, top, bottom|
|filter_<br>ignore_<br>net_names|Controls appearance of shorts/broken filter.<br>Default value is defined by the value of the configuration parameter<br>net_filter_short_broken_options.|


<h2 id="netlist_control">netlist_control</h2>

|----|----|
|Command| netlist_control|
|Group|Engineering Toolkit|
|Descr.|The command controls some aspects of the netlist analyzer window such as the auto zoom, layer mode and filters. A non specified parameter will retain its previous value.|

|----|----|
|Parameter| Value|
|auto_zoom| zoom_pan, pan_only or None|
|layers_<br>mode|Single, transparent, or multiple|
|filter1| A list of wild card expressions for top netlist|
|filter2| A list of wild card expressions for bot netlist|
|filter3| A list of wild card expressions for opt netlist|





<h2 id="netlist_cur2ref_compare">netlist_cur2ref_compare</h2>


|----|----|
|Command| netlist_cur2ref_compare|
|Group|Netlist|
|Descr.|The command calls the routine that compares between REFERENCE and CURRENT netlists and displays the results in the “Online Netlist Compare Window”.|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|display| None, top, bottom|

    Example #
    COM netlist_cur2ref_compare # ask for current netlist
    #
    if ($#COMANS == 0) then # array is empty
    echo "No current set"
    else
    echo "Number of broken is " $COMANS[1]
    echo "Number of Shorted is " $COMANS[2]
    echo "Number of Missing is " $COMANS[3]
    echo "Number of Extra is " $COMANS[4]
    endif



<h2 id="netlist_flip">netlist_flip</h2>

|----|----|
|Command| netlist_flip|
|Group|Engineering Toolkit|
|Descr.|The command flips over the CAD netlist, assigning bottom contact points to top and top points to bottom|

|----|----|
|Parameter |Value|
|job| Existing job name|
|step| Existing step name|


<h2 id="netlist_flip_mirror">netlist_flip_mirror</h2>
|----|----|
無



<h2 id="netlist_man_reg">netlist_man_reg</h2>

|----|----|
|Command| netlist_man_reg|
|Group|Engineering Toolkit|
|Descr.|The command registers the CAD netlist of a step (if exists) with the rest of the step manually.|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|dx| Shift in x|
|dy| Shift in y|


<h2 id="netlist_page_close">netlist_page_close</h2>

|----|----|
|Command| netlist_page_close|
|Group|Engineering Toolkit|
|Descr.|The command closes the netlist analyzer page. The current values remain intact until the next open.|


<h2 id="netlist_page_open">netlist_page_open</h2>

|----|----|
|Command| netlist_page_open|
|Group|Engineering Toolkit|
|Descr.|The command displays the netlist analyzer window and optionally sets the job/step/type values of the window|

|----|----|
|Parameter| Value|
|set| Yes - set fields with next parameters<br>No - do not set fields|
|job1| Existing job name|
|step1| Existing step name|
|type1| CAD, refnet, current, curcad|
|job2| Existing job name|
|step2| Existing step name|
|type2| CAD, refnet, current, curcad|



<h2 id="netlist_recalc">netlist_recalc</h2>

|----|----|
|Command| netlist_recalc|
|Group|Engineering Toolkit|
|Descr.|The command calculates the requested net and optionally displays the net names in the netlist analyzer window top or bottom part.|
|Response|Number of nets calculated/retrieved|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|type| CAD, refnet, current, curcad|
|display| Top, bottom|
|layer_list| List of layers appearing in the step<br>An example of a layer list is: layer_list1=bottom\;dr_plt\;rout\;|




<h2 id="netlist_ref_update">netlist_ref_update</h2>

|----|----|
|Command| netlist_ref_update|
|Group|Engineering Toolkit|
|Descr.|The command updates the reference netlist of a given step. The source can be the CAD netlist, the Current calculated netlist or ‘none’, in which case the reference will be deleted.|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|source| CAD, refnet, current, curcad, rtc, or None|
|radius| Value in mils. Default = 0.|





<h2 id="netlist_rotate">netlist_rotate</h2>

|----|----|

無

<h2 id="netlist_save_compare_results">netlist_save_compare_results</h2>

|----|----|
|Command| netlist_save_compare_results|
|Group|Netlist Analyzer|
|Descr.|The command format saves the netlist compare results into an output file.|


|----|----|
|Parameter| Value|
|out_file| Output file for the netlistcompare results (full pathname)|
|output| file, screen|
|filter_<br>ignore_net<br>_names|Controls Ignore Names filter for shorts/brokens|
|filter_nfp| Controls NFP Added/Removed filter for missing/extra|
|filter_<br>attr_diff|Controls Attribute Difference filter for<br>missing/extra|
|filter_<br>extra_on_<br>pad|Controls Extra Pads on Copper filter for missing/extra|



<h2 id="note_delete_all">note_delete_all</h2>
|----|----|
無

<h2 id="online_page_close">online_page_close</h2>

|----|----|
|Command| online_page_close|
|Group|Graphic Editor|
|Descr.|Pops up the **DRC** or **NETLIST** online page|

|----|----|
|Parameter| Value|
|type| Drc or netlist|


<h2 id="online_page_show">online_page_show</h2>

|----|----|
|Command| online_page_show|
|Group|Graphic Editor|
|Descr.|Pops up the DRC or NETLIST online page|

|----|----|
|Parameter| Value|
|type| DRC or netlist|


<h2 id="open_entity">open_entity</h2>

|----|----|
|Command| open_entity|
|Group|Engineering Toolkit|
|Descr.|Used for opening job children entities.|
|Response|group - group number of the step/symbol editor that is used in the ‘AUX set_group =group’ command.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|type|stackup, wheel,-matrix,step,attributes, panel_classes,wheel_template|
|name| Existing entity name|
|iconic| Yes, No|





<h3 id="open_entity_example">Example:</h3>
|----|----|

<pre style='color:#000000;background:#ffffff;'><span style='color:#005fd2; '>C-Shell</span> <span style='color:#0000e6; '>example</span>



<span style='color:#005fd2; '>open</span> <span style='color:#0000e6; '>step</span> <span style='color:#0000e6; '>context</span>

    <span style='color:#005fd2; '>COM</span> <span style='color:#0000e6; '>open_entity</span><span style='color:#44aadd; '>,</span> <span style='color:#0000e6; '>job=JOB</span><span style='color:#44aadd; '>,</span> <span style='color:#0000e6; '>type=step</span><span style='color:#44aadd; '>,</span> <span style='color:#0000e6; '>name=STEP</span>



<span style='color:#800000; font-weight:bold; '>switch</span> <span style='color:#0000e6; '>to</span> <span style='color:#0000e6; '>this</span> <span style='color:#0000e6; '>context</span>

    <span style='color:#0000e6; '>AUX</span> <span style='color:#0000e6; '>set_group</span><span style='color:#44aadd; '>,</span> <span style='color:#0000e6; '>group=</span><span style='color:#797997; '>$COMANS</span>
</pre>


<h2 id="open_job">open_job</h2>

|----|----|
|Command| open_job|
|Group|Engineering Toolkit|
|Descr.|The command is used for opening a job (reading it from the database into the memory).|


|----|----|
|Parameter |Value|
|job| Existing job name|



<h2 id="optimize_levels">optimize_levels</h2>

|----|----|
|Command|optimize_levels|
|Group|Graphic Editor|
|Descr.|The command is used for optimizing the number of positive negative levels.|
|Response|The number of positive negative levels after the operation.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|
|opt_layer| Optimized output layer|
|levels| Larger or equal to 1|





<h2 id="origin">origin</h2>

|----|----|
|Command| origin|
|Group|Graphic Editor|
|Descr.|Sets the graphic origin.|

|----|----|
|Parameter| Value|
|x, y| Legal coordinate|
|push_in_<br>stack|0 or 1 -<br>if 1 - new origin will be pushed into stack, enabling undo-origin command.|





<h2 id="origin_off">origin_off</h2>

|----|----|
|Command| origin_off|
|Group|Engineering Toolkit|
|Descr.|Switch the graphic origin off.|

<h2 id="origin_on">origin_on</h2>

|----|----|
|Command| origin_on|
|Group|Engineering Toolkit|
|Descr.|Switch the graphic origin on.|






<h2 id="output">output</h2>

|----|----|
|Command| output|
|Group|Engineering Toolkit|
|Descr.|Used for outputting steps data into external formats. The output is performed for all the layers that were defined using the command, **output_layer_set**.<br>NOTE: The **output** line mode command writes (to the log) only parameters relevant to the chosen format.|


|----|----|
|Parameter| Value|
|job| Existing job|
|step| Existing step|
|format|Gerber,Pentax,Gerber274x,Auto-plot,Image,Hpgl1,Hpgl2,DPF,Execllon1,|
|dir_path| File pathname - target directory|
|prefix| String - prefix for the layer formats (e.g - gerber)|
|suffix| String - suffix for the layer formats (e.g - gerber)|
|break_sr| Yes - the step & repeat data is broken into single layer<br>No - output step & repeat data - the parameters must a be YES for-<br>- Gerber,<br>- Gerber274x,<br>- Auto-plot,<br>- Hpgl1<br>- Hpgl2|
|break_<br>symbols|Yes - break special symbols (flat layer)<br>No - output special symbols<br>Note The parameters must be YES for hpgl1, hpgl2, execllon1,execellon2|
|break_arc| Yes - break arc features (flat layer)<br>No - output arc features|
|scale_mode| All - scale all features nocontrol scale all except control features control<br>Scale - scale only control features|
|surface_mode| Contour - Leave the surface as a contour (valid for -) fill - vectoric fill of the surfaces|
|min_brush| < min_brush <= 100.0 mils - for surface_mode == ‘fill’|
|units| Inch, mm (for gerber,,,etc)|
|coordinates| Absolute, incremental|
|zeroes| None, leading, trailing|
|nf1, nf2| Number format (1 <= n <= 6)|
|tool_units| Inch, mm (for drill formats)|
|x_anchor,<br>y_anchor|Legal coordinates for the layer transformations|
|wheel| Existing wheel name for gerber output|
|netlist_type| CAD - CAD<br>Reference - base line netlist<br>Current - current netlist<br>et_net - netlist created by ETM|
|line_units| Inch, mm - used for the command coordinates and sizes|
|override_<br>online|Yes,<br>No - used to override incomplete online status|
|intensity| For RPD|
|film_type| For RPD|
|film_size| For RPD|
|resolution| For RPD|
|priority| For RPD|
|no_copies| For RPD|
|params<br>_opt|Yes<br>No - for Print|
|orientation| Automatic, Portrait, Landscape - for Print|
|title_opt| Fix, Auto, Fix+Auto,None - for Print|
|title| Print title - for Print|
|size_mode| A0, A1,A2,A3, A4, A5, B4, B5, Letter, Life, Scale, Other - for Print|
|width| For Print|
|height| For Print|
|scale| For Print|
|circuitest| Yes<br>No|
|pads_<br>2circles|Yes<br>No - for Output of dxf pads ad 2 arcs or 1 empty circle|
|stagger| Yes<br>No - whether to output the staggered coor- -dinates or the base coordinates of a test point|
|test_thru| Yes - then thru- -holes that are mid points will never the less get tested in Probot output.<br>No -|
|test_ar_<br>above|Hole diameter in Mils/Micron - If 0 all holes are tested in the middle Otherwise - holes whose diameter is larger than this val will be tested on their annular rings|
|finished<br>_drills|Yes<br>No - Whether to output the finished drill hole size or layer size
|feature_dim| Yes<br>No - Whether to output feature dimentions to hole size in IPC|
|draft| Yes<br>No - For output of drawing files in draft mode in DXF output|
|nom_space| Nominal spacing Mil/Mic - Llyod Doyle format|
|nom_track| Nominal track width Mil/mic - Llyod Doyle format|
|auto_purge| Yes - Purge plotter outputs<br>No - Do not purge plotter output|
|entry_num| 1-999 For plotter outputs|
|plot_copies| 1-255 For plotter outputs|
|dp100x_<br>alignment|Edge alignment for plotter outputs<br>2 point standard<br>3 point minimal<br>4 point split axis<br>Point averaging|
|dp100x_clip| Center, Absolute - Plotter outputs|
|dp100x_<br>lamination|Lamination options for plotter outputs<br>Single<br>Foil<br>Sheet<br>Other|
|dp100x_<br>iserial|Plotter outputs|
|ins_s_drills| Values = Yes, No. For Lloyd Doyle output.|
|send_to_<br>plotter|Yes, No, None|
|cool_spread| Defines the minimal distance (in current units [mil/microns]) between succeeding hits during the board drilling process. This value is used in optimization.|

<h2 id="output_layer_reset">output_layer_reset</h2>

|----|----|
|Command| output_layer_reset|
|Group|Engineering Toolkit|
|Descr.|The command resets that output layers list, which is used by the output command.|



<h2 id="output_layer_set">output_layer_set</h2>

|----|----|
|Command| output_layer_set|
|Group|Engineering Toolkit|
|Descr.|The command adds a layer to the output list (layer name and transformation parameters).|

|----|----|
|Parameter| Value|
|layer| Existing layer name|
|angle| 0, 90, 180, 270|
|mirror| Yes, No - around X axis|
|x_scale,<br>y_scale|95 < scale <= 1.05 only the feature coordinates are scaled|
|comp| -10 <= comp <= 10 (mils)compensation(resize) value|
|polarity| Positive, negative - used for: 274x, and image (panel header)|
|line_units| Inch, mm - used for the command coordinates and sizes|
|setupfile| Existing setupfile name|
|setupfile_<br>active|TRUE, FALSE|




<h2 id="pan_center">pan_center</h2>

|----|----|
|Command| pan_center|
|Group|Graphic Editor|
|Descr.|Pan the center of the screen to a specified coordinate.|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates|


<h2 id="pan_down">pan_down</h2>

|----|----|
|Command| pan_down|
|Group|Graphic Editor|
|Descr.|Pan down the graphic display.|


|----|----|
|Parameter| Value|
|percent| 1.0 - 100.0|




<h2 id="panel_size">panel_size</h2>

|----|----|
|Command| panel_size|
|Group|Graphic Editor|
|Descr.|Sets the panel (step) profile as a rectangle with a specified size.|


|----|----|
|Parameter| Value|
|width,<br>height|0 <= size (inches)|


<h2 id="pan_feat">pan_feat</h2>

|----|----|
|Command| pan_feat|
|Group|Graphic Editor|
|Descr.|Pan to a specified layer feature.|

|----|----|
|Parameter| Value|
|layer| step layer name|
|index| existing feature index (< 1)|
|auto_zoom| Yes - the display is zoommed according to the feature size<br>No - only panning|



<h2 id="pan_left">pan_left</h2>

|----|----|
|Command| pan_left|
|Group|Graphic Editor|
|Descr.|Pan left the graphic display.|

|----|----|
|Parameter| Value|
|percent| 1.0 - 100.0|



<h2 id="pan_right">pan_right</h2>

|----|----|
|Command| pan_right|
|Group|Graphic Editor|
|Descr.|Pan right the graphic display.|


|----|----|
|Parameter| Value|
|percent| 1.0 - 100.0|



<h2 id="pan_up">pan_up</h2>

|----|----|
|Command| pan_up|
|Group|Graphic Editor|
|Descr.|Pan up the graphic display.|

|----|----|
|Parameter| Value|
|percent| 1.0 - 100.0|

<h2 id="print">print</h2>

|----|----|
|Command| print|
|Group|Graphic Editor|
|Descr.|Prints graphic layers in pdf or postscript format.|

|----|----|
|Parameter| Value|
|title| Allows a title to be printed at the top of each page.|
|layer_name| A semicolon separated list of layers. All layer types are supported.|
|dest| printer,preview,postscript,pdf|
|num_copies| Number of copies desired|
|dest_fname| Name of file to create when dest is pdf or postscript|
|paper_size|A0,A1,A2,A3,A4,A5<br>B4,B5<br>Letter<br>Other|
|nx| number of images in horizontal axis|
|ny| number of images in vertical axis|
|orient| portrait, landscape, none (i.e. system to choose orientation)|
|paper_<br>orient|portrait, landscape|
|paper_width| Paper width in inches, when "other" paper_size is specified|
|paper_length |Paper length in inches, when "other" paper_size is specified|
|auto_tray|-|
|top_margin| page margin|
|bottom_margin| page margin|
|left_margin| page margin|
|right_margin| page margin|
|x_spacing| horizontal spacing between images|
|y_spacing| Reserved for future use|



<h2 id="profile_poly_end">profile_poly_end</h2>

|----|----|
|Command |profile_poly_end|
|Group|Graphic Editor|
|Descr.|Closes a profile polygon.|


<h2 id="profile_poly_seg">profile_poly_seg</h2>

|----|----|
|Command| profile_poly_seg|
|Group|Graphic Editor|
|Descr.|Adds a polygon segment.|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - segment end point|




<h2 id="profile_poly_strt">profile_poly_strt</h2>

|----|----|
|Command| profile_poly_strt|
|Group|Graphic Editor|
|Descr.|Starts a profile polygon.|

|----|----|
|Parameter| Value|
|x, y| Legal coordinates - start point|

<h2 id="profile_rect">profile_rect</h2>

|----|----|
|Command| profile_rect|
|Group|Graphic Editor|
|Descr.|Defines a rectangular step profile.|

|----|----|
|Parameter| Value|
|x1, y1,<br>x2, y2|Legal coordinates - rectangle corners|





<h2 id="profile_to_rout">profile_to_rout</h2>

|----|----|
|Command| profile_to_rout|
|Group|Graphic Editor|
|Descr.|The command converts a step profile into a rout layer. If the layer does not exist, it will be created.|

|----|----|
|Parameter| Value|
|layer| Legal rout layer name line width|
|width| 0 <= width <= max size (mils) - line width|



<h2 id="pull_feat">pull_feat</h2>

|----|----|
|Command| pull_feat|
|Group|Graphic Editor|
|Descr.|Pulls a line feature into 2 connected lines.|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|tol| 0 <= tol (mils) - snap tolerance|
|x1s,y1s,<br>x1e,y1e|(Descr.) - line number 1|
|x2s,y2s,<br>x2e,y2e|(Descr.) - line number 1|





<h2 id="recover_lost_jobs">recover_lost_jobs</h2>

|----|----|
|Command| recover_lost_jobs|
|Group| Engineering Toolkit|
|Descr.| Add entries to the joblist for each job directory in a database that is not in the joblist.|




<h2 id="remove_hole">remove_hole</h2>

|----|----|
|Command| remove_hole|
|Group|Graphic Editor|
|Descr.|Removes a contour hole (must be a hole with no inner islands).|

|----|----|
|Parameter| Value|
|x,y| Legal coordinates (inch/mm) - coordinates of a point within the hole to be moved.|



<h2 id="remove_vertex">remove_vertex</h2>

|----|----|
|Command| remove_vertex|
|Group|Graphic Editor|
|Descr.|Removal of contour vertex|

|----|----|
|Parameter| Value|
|x,y| Legal coordinates (inches/mm) - coordinates of vertex.|





<h2 id="rename_entity">rename_entity</h2>


|----|----|
|Command| rename_entity|
|Group|Engineering Toolkit|
|Descr.|Used for renaming entities.|

|----|----|
|Parameter| Value|
|job| Name of an existing opened job|
|is_fw| Yes - framework entity (form, flow- according to the fw_type parameter)<br>No - CAM entity (according to the type param)|
|type| - Job<br>- Step<br>- Symbol<br>- Stackup<br>- Wheel<br>- Matrix - symbol renaming is not supported at this stage|
|fw_type| Form, flow|
|name| Existing entity name|
|new_name| Entity name|




<h2 id="rename_layer">rename_layer</h2>

|----|----|
|Command| rename_layer|
|Group|Graphic Editor|
|Descr.|The command is used for renaming a layer (the matrix is updated).|

|----|----|
|Parameter| Value|
|name |Existing layer name|
|new_name| Entity name of a non-existing layer|




<h2 id="rerout_trace">rerout_trace</h2>

|----|----|
無



<h2 id="rotate_feat">rotate_feat</h2>

|----|----|
|Command| rotate_feat|
|Group|Graphic Editor|
|Descr.|Rotates a feature around it’s axis point.|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|angle| 0, 90, 180, 270|
|tol| 0 <= tol (mils) - snap tolerance|




<h2 id="rotate_step">rotate_step</h2>

|----|----|
|Command| rotate_step|
|Group|Graphic Editor|
|Descr.|The command creates a step entry (column) in a job matrix by rotating the existing step.|


|----|----|
|Parameter| Value|
|name| name of existing open job|
|step| existing step name|
|rotated_<br>step|rotated step name|
|angle| rotation angle|
|mode| rotation mode: datum, center, or anchor<br>datum - step datum point<br>center- step profile center<br>anchor- arbitrary point|
|units| Units for anchor point coordinates definition.<br>Possible values = inches or mm.
|anchor_x,<br>anchor_y|legal coordinates for rotation anchor point|



<h2 id="save_job">save_job</h2>

|----|----|
|Command| save_job|
|Group|Engineering Toolkit|
|Descr.|Used for saving a job (the changed entities are written to the database).|


|----|----
|Parameter| Value|
|job| Name of an existing opened job|
|override| Yes to override online violations|


**Note** The **y2k_last_saved** configuration parameter determines the use of 4-
digit year format in the **last_saved** stamp.



<h2 id="script_record">script_record</h2>

|----|----|
|Command| script_record|
|Group|Scripts|
|Descr.|Enable/Disable recording mode|

|----|----|
|Parameter| Value|
|mode| abs,inc,stop inc not supported|
|append| Yes, No append to session|



<h2 id="script_run">script_run</h2>

|----|----|
|Command| script_run|
|Group|Scripts|
|Descr.|Run a script|

|----|----|
|Parameter| Value|
|name| Script name - according to dir mode or full path if starts with /|
|dirmode| Local/global - see name|
|params| Script params|
|env1| Environment variable setting, e.g. JOB=jobname|
|env2| e.g. STEP=stepname|
|env3| e.g. STEP=stepname|
|env4| e.g. STEP=stepname|



<h2 id="sel_all_feat">sel_all_feat</h2>

|----|----|
|Command| sel_all_feat|
|Group|Graphic Editor|
|Descr.|Selects all the features in all the affected layers.|



<h2 id="sel_break">sel_break</h2>

|----|----|
|Command| sel_break|
|Group|Graphic Editor|
|Descr.|Breaks all the selected features that are composed from special symbols into their primitives (round + square symbols).|


<h2 id="sel_buffer_clear">sel_buffer_clear</h2>

|----|----|
|Command| sel_buffer_clear|
|Group|Graphic Editor|
|Description|Clears the buffer (frees unused memory).|



<h2 id="sel_buffer_copy">sel_buffer_copy</h2>

|----|----|
|Command| sel_buffer_copy|
|Group|Graphic Editor|
|Descr.|The command copies all the selected features into the selection buffer (features can be pasted by the - sel_buffer_paste command).|

|----|----|
|Parameter| Value|
|x_datum,<br>y_datum|Legal coordinates - pushed for the ‘paste’ operation|



<h2 id="sel_buffer_cut">sel_buffer_cut</h2>

|----|----|
|Command| sel_buffer_cut|
|Group|Graphic Editor|
|Descr.|The selected features are deleted after being copied to buffer.|




<h2 id="sel_buffer_option">sel_buffer_option</h2>

|----|----|
|Command| sel_buffer_options|
|Group|Graphic Editor|
|Descr.|Defines the behavior of specific buffer operations, via the Buffer Options Popup.|



<h2 id="sel_buffer_paste">sel_buffer_paste</h2>

|----|----|
|Command| sel_buffer_paste|
|Group|Graphic Editor|
|Descr.|The command pastes the contents of the selection buffer in the affected layers at the specified location.|


|----|----|
|Parameter| Value|
|x, y| Legal coordinates - paste position|


<h2 id="sel_change_atr">sel_change_atr</h2>

|----|----|
|Command| sel_change_atr|
|Group|Graphic Editor|
|Descr.|The command changes the attributes of all the selected features. The attribute values are set according to the cur_atr_set command (which sets the current attribute values).|


|----|----|
|Parameter| Value|
|mode| Add - add the new attribute values to the existing ones<br>Replace - replace the existing attributes by the new ones|



<h2 id="sel_change_sym">sel_change_sym</h2>

|----|----|
|Command| sel_change_sym|
|Group|Graphic Editor|
|Descr.|Changes the symbol of all the selected features (lines,pads,arcs).|

|----|----|
|Parameter| Value|
|symbol| Existing symbol|
|reset_<br>angle|Controls angle of rotated pads. Possible values:<br>Yes =Reset the angle of a rotated pad.<br>No = Do not reset the angle of a rotated pad.|


<h2 id="sel_change_text">sel_change_text</h2>

|----|----|
|Command| sel_change_txt|
|Group|Graphic Editor|
|Descr.|Changes the text of all the selected (text) features|

|----|----|
|Parameter| Value|
|text| Text string|
|x_size,<br>y_size|Size of text in inches or mm|
|w_factor| Font line width coefficient. The coefficient is calculated in units of 12 mils.<br>For example:<br>1 = a width of 12 mils.<br>1.5 = a width of 18 mils.<br>2 = a width of 24 mils.|



<h2 id="sel_clear_feat">sel_clear_feat</h2>

|----|----|
|Command| sel_clear_feat|
|Group|Graphic Editor|
|Descr.|Un-selects all the features in all the affected layers.|


<h2 id="sel_cont2pad">sel_cont2pad</h2>

|----|----|
|Command| sel_cont2pad|
|Group|Graphic Editor|
|Descr.|Transforms selected contours into matching pads|


|----|----|
|Parameter| Value|
|match_tol| Tol >= 0<br>Tol <= 5.0 mils - tolerance to use for connections|
|restriction|A mask composed of the following options:<br>0 - No restrictions<br>1 - Only symmetric symbols<br>2 - A single island contour<br>4 - Only standard symbols<br>8 - Enable contour<br>Comment: A set of limitations on the type of created contour|
|min_size| 0.01 mils <= min_size <= 10 mils|
|max_size| 1 mil < max_size <= 500 mils|
|suffix| Backup layer suffix|




<h2 id="sel_contourize">sel_contourize</h2>

|----|----|
|Command| sel_contourize|
|Group|Graphic Editor|
|Descr.|The command converts all the selected features into contour (surface) features.|


|----|----|
|Parameter| Value|
|accuracy| Double value 0 < accuracy < 2 mil. Specifies a maximum allowable distance between selected feature and resulting contour|
|break_to<br>_islands|Yes / No<br>Yes - each island will be created as a separate surface, otherwise all islands will be in one surface.|
|clean_hole<br>_size|0.0<= size <= 8000.0 mils - The minimum size of hole that can be created.|
|clean_hole<br>_mode|x_or_y, x_and_y, area - The mode of the minimum size measurement.|



<h2 id="sel_cont_resize">sel_cont_resize</h2>

|----|----|
|Command| sel_cont_resize|
|Group|Graphic Editor|
|Descr.|Contourizes and resizes the selected features.|

|----|----|
|Parameter| Value|
|accuracy| Double value 0< accuracy <2 mil<br>Specifies a maximum allowed distance between selected feature and resulting contour.|
|break_to_<br>islands|Yes / No<br>Yes - each island will be created as a separate surface.<br>No - all islands will be one surface.|
|island_size| -8000 <= size <= 8000 mils|
|hole_size| -8000 <= size <= 8000 mils|
|drill_filter| Boolean<br>True - use step’s Drill Filter to filter holes.



<h2 id="sel_copy">sel_copy</h2>

|----|----|
|Command| sel_copy|
|Group|Graphic Editor|
|Descr.|Copies all the selected features.|

|----|----|
|Parameter| Value|
|dx, dy| Legal coordinates - copy offset|



<h2 id="sel_copy_other">sel_copy_other</h2>

|----|----|
|Command |sel_copy_other|
|Group|Graphic Editor|
|Descr.|Copies all the selected features to a specified layer.|


|----|----|
|Parameter| Value|
|dest| affected_layers - copy to all affected layers except for the layer that includes the selected features<br>layer_name - use the ‘target_layer’|
|target_<br>layer|If the layer does not exist - it will be created.|
|invert| Yes, No<br>invert polarity|
|dx, dy| Offset|
|size| Resize by (mils)|
|x_anchor| xxxxx|
|y_anchor| yyyyy|
|rotation| [0 - 360] degrees|
|mirror| [none, horizontal, vertical]|





<h2 id="sel_copy_repeat">sel_copy_repeat</h2>

|----|----|
|Command| sel_copy_repeat|
|Group|Graphic Editor|
|Descr.|The command step & repeats the selected features.|

|----|----|
|Parameter| Value|
|nx, ny| >= 0 - Number of repeats|
|dx, dy| Distance between repeats|




<h2 id="sel_create_profile">sel_create_profile</h2>

|----|----|
|Command| sel_create_profile|
|Group|Graphic Editor|
|Descr.|The command is used for creating a step profile from the selected features. The skeleton shapes of all the line/arc features are taken as a closed polygon. Gaps are closed by connecting segments.|


<h2 id="sel_create_step">sel_create_step</h2>

|----|----|
|Command| sel_create_step|
|Group|Graphic Editor|
|Descr.|The command creates a step (multiple layers) based on the selected features. The new step is added to the job matrix. If the step already exists - it will be overwritten|

|----|----|
|Parameter| Value|
|step| Entity name - created step name|
|x_datum,<br>y_datum|Legal coordinates step datum point|
|delete| Yes - delete the selected features after the operation is complete<br>No - no delete|




<h2 id="sel_cut_data">sel_cut_data</h2>

|----|----|
|Command| sel_cut_data|
|Group|Graphic Editor|
|Descr.|Transforms selected features to polygons / contours|

|----|----|
|Parameter| Value|
|con_tol| Tol >= 0.01<br>Tol <= 100.0 mils - maximum gap size that will be repaired automatically|
|det_tol| Tol >= 0.01<br>Tol <= 100.0 mils - maximum detected and reported gap size|
|rad_tol| Tol >= 0<br>Tol <= 5.0 mils - smoothing tolerance|
|filter_<br>overlaps|Yes - to join overlaping and collinear segments before processing<br>No - to leave them as is|
|use_order| Yes - if possible rely on the input order of features in layer<br>No - rely only on geometry|
|delete_<br>doubles|Yes - delete duplicate features from the layer<br>No - don’t delete duplicate features from the layer|
|ignore_<br>width|Yes - use only skeletons of arcs and lines<br>No - use line width|
|ignore_<br>holes|Yes - ignore embedded polygones<br>No - enter embedded poly as holes|

When run from a script, **sel_cut_data** sets a response string in the global
$COMANS variable. The string format is **cont probl warn info**, where

- **cont** - number of created contours
- **probl** - number of detected problems (number of items in red zone)
- **warn**- number of generated warnings (number of items in yellow zone)
- **info** - number of generated info items (number of items in green zone)


<h2 id="sel_delete">sel_delete</h2>

|----|----|
|Command| sel_delete|
|Group|Graphic Editor|
|Descr.|Deletes all the selected features.|

<h2 id="sel_delete_atr">sel_delete_atr</h2>

|----|----|
|Command| sel_delete_atr|
|Group|Graphic Editor|
|Descr.|The command is used for deleting (removing) attribute assignments for all the selected features.|

|----|----|
|Parameter| Value|
|attributes| Existing attribute names separated by ‘;’ characters|
|mode| list - (default) the attributes defined in the parameter attributes will be deleted - all<br>feature(s) attributes will be deleted (in this case parameter attributes not used)



<h2 id="sel_drawn">sel_drawn</h2>


|----|----|
|Command| sel_drawn|
|Group|Graphic Editor|
|Descr.|To select drawn surfaces|

|----|----|
|Parameter |Value|
|type| - Crosshatch<br>- Mixed<br>- Power ground <br>Defines a type of layer/fill used in the layer. Parameters of algorithm will change according to the type specified.|
|therm_analyze|Yes - drawn thermal pads will be excluded from contourization.|

<h2 id="sel_fill">sel_fill</h2>


|----|----|
|Command| sel_fill|
|Group|Graphic Editor|
|Descr.|Fills all the selected **SURFACE** features. The filling is performed according to the fill_params command.|




<h2 id="sel_intersect_coord">sel_intersect_coord</h2>

|----|----|
|Command| sel_intersect_coord|
|Group|Graphic Editor|
|Descr.|The command performs an intersection of two features that have been previously selected. The intersection can be a regular corner, an arc or a chamfer. choose the center point closest to x, y|


|----|----|
|Parameter| Value|
|function| find_contact - between lines<br>find_circle - between lines<br>find_plines - connecting arcs - or arc & pad by line<br>find_lines - connecting arcs - or arc & arc by arc<br>find_arcs - connecting non-intersecting lines and circles by arc|
|mode| Corner - regular intersection<br>Round - rounded corner<br>Chamfer - chamfer corner|
|radius| -100000 <= size <= 100000 mils radius for round|
|length_x| -100000 <= size <= 100000 mils length1 for chamfer|
|length_y |-100000 <= size <= 100000 mils length2 for chamfer|
|type_x| Length / angle|
|type_y| Length / angle|
|x, y| Legal coordinates - feature coordinates|
|x2, y2| Coordinates of an additional point near a tangent line. For use only when function = find_plines. (See function parameter above)|
|show_all| Yes - all options<br>No -|
|keep_<br>remainder1|Yes - leave rest of features|
|keep_<br>remainder2|Yes - leave rest of features<br>No -|
|ang_x| Angle for chamfer|
|ang_y| Angle|





<h2 id="sel_invert">sel_invert</h2>

|----|----|
|Command| sel_invert|
|Group|Graphic Editor|
|Descr.|Inverts the polarity of all the selected features.|


<h2 id="sel_layer_feat">sel_layer_feat</h2>


|----|----|
|Command| sel_layer_feat|
|Group|Graphic Editor|
|Descr.|Used for selecting a single feature in a specified layer.|

|----|----|
|Parameter| Value|
|operation| Select / unselect|
|layer| Entity name - step layer|
|index| Existing feature index|



<h2 id="sel_line2pad">sel_line2pad</h2>

|----|----|
|Command| sel_line2pad|
|Group|Graphic Editor|
|Descr.|The command converts all the selected lines that have zero length into pads.|


<h2 id="sel_move">sel_move</h2>

|----|----|
|Command| sel_move|
|Group|Graphic Editor|
|Descr.|Moves (shifts) all the selected features.|

|----|----|
|Parameter| Value|
|dx, dy| Legal coordinates - shift values|



<h2 id="sel_move_other">sel_move_other</h2>

|----|----|
|Command| sel_move_other|
|Group|Graphic Editor|
|Descr.|Moves all the selected features to a specified layer.|

|----|----|
|Parameter| Value|
|dx, dy| Offset|
|invert| Yes, No - invert polarity|
|mirror| [none, horizontal, vertical]|
|rotation| [0 - 360] degrees|
|size| Resize by (mils)|
|target_<br>layer|If the layer does not exist it will be created|
|x_anchor| xxxxx|
|y_anchor| yyyyy|



<h2 id="sel_multi_feat">sel_multi_feat</h2>

|----|----|
|Command| sel_multi_feat|
|Group|Graphic Editor|
|Descr.|Used for selecting multiple features according to specified filters. The selection is performed on all the affected layers.|


|----|----|
|Parameter| Value|
|operation| Select, Unselect|
|feat_types| - line<br>- pad<br>- surface<br>- arc<br>- text ‘set’ field|
|include_<br>syms|Wild symbol names (separated by ‘;’ characters).|


<h2 id="sel_net_feat">sel_net_feat</h2>

|----|----|
|Command| sel_net_feat|
|Group|Graphic Editor|
|Descr.|Selects all the features that are part of the same net. The operation is performed on the work layer.|

|----|----|
|Parameter| Value|
|operation| Select, unselect|
|x, y|Legal coordinates - feature coordinates|
|tol| 0 <= tol <= max coord - snap tolerance|
|use_ffilter|Values = [no/yes] (default = no)|




<h2 id="sel_options">sel_options</h2>

|----|----|
|Command| sel_options|
|Group|Graphic Editor|
|Descr.|Setting selection options that are used by the ui popup.|

|----|----|
|Parameter |Value|
|clear_mode| - clear_after - clears the selected feat after an edit operation<br>- clear_none - the selection remains|
|display_<br>mode|- displayed_layers - display the selected features of the displayed layers only <br>- all_layers - display the selected features of all the affected layers
|area_inout| - Inside - select features that are inside the specified area<br>- Outside - select features that are outside the specified area
|area_<br>select|Select, Unselect|




<h2 id="sel_orthogonal_stretch">sel_orthogonal_stretch</h2>

|----|----|
|Command| sel_orthogonal_stretch|
|Group|Graphic Editor|
|Descr.|Moves and stretches a group of features that cross the rectangle limits in the opposite direction to the stretch|

|----|----|
|Parameter| Value|
|diff| movement_amount|
|direction| Direction of stretching(4)|
|x_s, y_s,<br>x_e, y_e|Rectangle selected|



<h2 id="sel_pad2outline">sel_pad2outline</h2>

|----|----|
|Command| sel_pad2outline|
|Group|Graphic Editor|
|Descr.|Used to reshape the big drill to rout path.|



<h2 id="sel_pad2slots">sel_pad2slots</h2>

|----|----|
|Command| sel_pads2slots|
|Group|Graphic Editor|
|Descr.|Replaces all selected pads with slots of a given symbol, length, angle, dcode, and drill_type. Pad ‘s position of center and attributes (except for .drill attributes) will be copied into slot.|

|----|----|
|Parameter| Value|
|symbol| Entity name - slot symbol name|
|len| Positive value - replacing slot len(inch/mm)|
|center_<br>shift|Legal coordinates - allows optional shifting of slot center relative to replaced pad center; direction depends on angle of slot|
|angle| Positive integer (0 - 360) - replacing slot angle(deg)|
|slot_dcode| Positive integer (0-> no dcode) - replacing slot dcode|
|drill_type| plate - plated hole<br>nplate - non-plated hole<br>via - via hole|




<h2 id="sel_polarity">sel_polarity</h2>

|----|----|
|Command| sel_polarity|
|Group|Graphic Editor|
|Descr.|Changes the polarity of all the selected features.|



<h2 id="sel_polarity_invert">sel_polarity_invert</h2>

|----|----|
無


<h2 id="sel_polyline_feat">sel_polyline_feat</h2>


|----|----|
|Command| sel_polyline_feat|
|Group|Graphic Editor|
|Descr.|Used for selecting all features belongs to the polyline crossing point (x,y) in all of the affected layers.|

|----|----|
|Parameter| Value|
|operation| Select, unselect|
|x, y| Legal coordinates - feature snap coordinates|
|tol| 0 <= tol - snap tolerance|



<h2 id="sel_ref_feat">sel_ref_feat</h2>

|----|----|
|Command| sel_reference|
|Group|Graphic Editor|
|Descr.|Selecting features by reference filter|


|----|----|
|Parameter| Value|
|layer| A list of layers separated by semicolons.|
|use| What to use as a reference<br>Filter - use the filter parameters on the reference layers features<br>Select - use the selected features of the reference layers|
|mode| Mode of reference selection<br>Touch - take all features touch reference features<br>Disjoint - take all features not touching any reference features<br>Cover - take all features fully covered by at least one reference feature<br>Include - take all features that fully include at least one reference feature|
|f_types| - Line<br>- Pad<br>- Surface<br>- Arc<br>- Text - set field|
|polarity| Positive / Negative - ‘set field’|
|include_syms| Wild symbol names (separated by ‘;’ characters). area|
|exclude_syms| Wild symbol names separated symbol names to be by ‘;’ characters - exclude|


**Ranges for Symbol Names**
You can define a range of Genesis symbols for use in selected Genesis filters, line
mode commands, and popups. Two standard or semi-standard symbol names of the
same type separated by a colon (:) define the range of symbols. All existing Genesis
symbol types may be included in the list.

Any symbol filter may be defined as a list of symbol definition names separated by a
semicolon (;). Symbol definition names may be written using any of the following
rules:

- Any legal symbol name.
- Wild card name (a name with an asterisk mark (*).
Examples: "s*" or "rect100x*" or "rect*x50" .
- Note: The symbol definition name * (used by itself) means no filter. (All symbol
names are ignored.)
r100:r300: matches all round symbols between 100 (inclusive) and 300
(inclusive). It matches r100 , r100.1 , r150.34 , r300, but does not match
r99.99 or r300.1.

rect20x30: rect100x50 matches all rectangle symbols where the width is
between 20 and 100 and the length is between 30 and 50. It therefore matches
rect20x40, rect100x50, and rect20.123x99.999, but does not match
rect20x100.1

Also applicable to Reference Selection Popup and Features Filter Popup. See
Doc. 0601, The Graphic Editor, for more information.



<h2 id="sel_resize">sel_resize</h2>

|----|----|
|Command| sel_resize|
|Group|Graphic Editor|
|Descr.|Resizes all the selected features (enlarges or shrinks). Special symbol features are not affected by the command.|

|----|----|
|Parameter| Value|
|size| -8000 <= size <= 8000 mils|



<h2 id="sel_resize_poly">sel_resize_poly</h2>

|----|----|
|Command| sel_resize_poly|
|Group|Graphic Editor|
|Descr.|Resizes a polygon that is formed by a series of selected features.|

|----|----|
|Parameter| Value|
|size| -8000 <= size <= 8000 mils|



<h2 id="sel_resize_surface">sel_resize_surface</h2>

|----|----|
|Command| sel_resize_surface|
|Group|Graphic Editor|
|Descr.|Resizes all the selected surface features (enlarges or shrinks).|

|----|----|
|Parameter| Value|
|island_<br>size|-8000 <= size <= 8000 mils|
|hole_size| -8000 <= size <= 8000 mils|
|drill_<br>filter|Boolean - If true, use the step’s Drill Filter to filter holes.


<h2 id="sel_reverse">sel_reverse</h2>

|----|----|
|Command| sel_reverse|
|Group|Graphic Editor|
|Descr.|Used to unselect all the selected features, and select the unselected ones.|



<h2 id="sel_single_feat">sel_single_feat</h2>

|----|----|
|Command| sel_single_feat|
|Group|Graphic Editor|
|Descr.|Used for selecting a single feature in all of the affected layers.|

|----|----|
|Parameter| Value|
|operation| Select, unselect|
|x, y| Legal coordinates - feature snap coordinates|
|tol| 0 <= tol - snap tolerance|
|cyclic| Yes - allow cyclic selection<br>No - no -cyclic selection|



<h2 id="sel_stretch">sel_stretch</h2>

|----|----|
|Command| sel_stretch|
|Group|Graphic Editor|
|Descr.|Stretches a group of selected parallel lines.|

|----|----|
|Parameter| Value|
|index| Line feature index|
|start| Yes - stretch start point<br>No - stretch end point|
|x_new,<br>y_new|New start / end location|


<h2 id="sel_surf2outline">sel_surf2outline</h2>

|----|----|
|Command| sel_surf2outline|
|Group| Graphic Editor|
|Descr.| To convert legal Genesis surfaces to sequences of lines and arcs.|

|----|----|
|Parameter| Value|
|width| Width of features (lines and arcs) Range: [0.0 …8000.0 mils]|


<h2 id="sel_transform">sel_transform</h2>

|----|----|
|Command| sel_transform|
|Group|Graphic Editor|
|Descr.|The command transforms all the selected features. Scaling of the features affects only the location. When rotating by an angle that is not a 90 degrees multiple, the special symbols are not rotated (only the features location).|


|----|----|
|Parameter| Value|
|mode|Anchor - transformations are performed around a specified anchor point<br>axis around each feature axis point
|oper| Rotate;mirror;scale(mirror - in X axis) (mirror - in Y axis) - ‘set’ field|
|duplicate| No - operate on the selected features<br>Yes - duplicate the selected features, and transform the duplicated ones|
|x_anchor,<br>y_anchor|Legal coordinates - if mode == anchor|
|angle| 0.0 - 360.0 - if oper == rotate|
|x_scale,<br>y_scale|0.0 - 1e6.... - if oper == scale|
|x_offset,<br>y_offset|



<h2 id="set_attribute">set_attribute</h2>

|----|----|
|Command| set_attribute|
|Group|Engineering Toolkit|
|Descr.|The routine is used for setting entity attributes.|

|----|----|
|Parameter| Value|
|type| - Job<br>- Step<br>- Symbol<br>- Layer<br>- Wheel - entity type|
|job| existing job name|
|name1| for type!= job|
|name2| for type = layer|
|name3||
|attribute| existing attribute name|
|value| attribute value (string)|
|units| For units-dependent attributes. You can specify an attribute value in metric units(units=mm), and the value will be automatically converted to imperial units (either inches or mils, depending on attribute definition in the sysattr file). Either way, the attribute value is stored in *imperial* units.|




<h2 id="set_group">set_group</h2>

|----|----|
|Command| set_group|
|Group|None|
|Descr.|Sets the group context of the current script. This command is run using AUX rather than COM.|

|----|----|
|Parameter| Value|
|group| Group number of desired context|



<h2 id="set_out_name_attr">set_out_name_attr</h2>

|----|----|
|Command| set_out_name_attr|
|Group|Engineering Toolkit|
|Descr.|The routine is used for setting out_name step attribute.|
|Response|None|

|----|----|
|Parameter| Value|
|job| Existing job name|
|step| Existing step name|
|value| Attribute value (string)|


<h2 id="show_form">show_form</h2>

|----|----|
|Command| show_form|
|Group|Work Forms|
|Descr.|Displays a given form|

|----|----|
|Parameter| Value|
|job| Name of the job|
|form| Name of the form|
|updonly| Yes - only update (if displayed)<br>No - Displays always|
|updelem| Name of the element to update (If updonly=YES)|



<h2 id="skip_current_command">skip_current_command</h2>

|----|----|
|Command| skip_current_command|
|Group|Clipboard|
|Descr.|Prevents the line mode command to which this “pre” hook belongs from running, without preventing an error. This line mode command may be run only in a “pre” hook.<br>**Note:** The other method of preventing a line mode command from running (exiting with nonzero status) generates an error.<br>**Note:** See Appendix A to see this line mode command in use.|


<h2 id="skip_next_pre_hook">skip_next_pre_hook</h2>

|----|----|
|Command| skip_next_pre_hook|
|Group|Clipboard|
|Descr.|Prevents the system from running the “pre” hook of the next line mode command that is run. If the line mode command that is run does not have a “pre” hook, this command has no effect.<br>**Note:** See Appendix A to see this line mode command in use.|


<h2 id="snap_features">snap_features</h2>

|----|----|
|Command| snap_features|
|Group|Graphic Editor|
|Description|The snap_features command is used for setting the snap features to be used as snap features filter.|

|----|----|
|Parameter| Value|
|feat_types| Sets feature type. Possible values: line, pad, surface, arc, text, set field.|


<h2 id="snap_layer">snap_layer</h2>

|----|----|
|Command| snap_layer|
|Group|Graphic Editor|
|Description|The snap_layer command is used for setting the snap layer.|


|----|----|
|Parameter| Value|
|name| Existing layer name|


<h2 id="snap_mode">snap_mode</h2>

|----|----|
|Command| snap_mode|
|Group|Graphic Editor|
|Description|The snap_mode command is used for setting the snap mode|

|----|----|
|Parameter| Value|
|mode| Sets snap mode. Possible values: off ,grid, center, skeleton, edge, intersect, midpoint,profile.|


<h2 id="split_edge">split_edge</h2>

|----|----|
|Command| split_edge|
|Group|Graphic Editor|
|Description|Splitting of a contours edge.|


|----|----|
|Parameter| Value|
|x,y| Legal coordinates (inch/mm) coordinates of split point.|




<h2 id="sr_active">sr_active</h2>

|----|----|
|Command| sr_active|
|Group|Graphic Editor|
|Descr.|Sets the step & repeat active area margins.|

|----|----|
|Parameter| Value|
|top,<br>bottom,<br>left,<br>right|0 < = size (the sizes must form a rectangle that is smaller than the panel size)|


<h2 id="sr_auto">sr_auto</h2>

|----|----|
|Command| sr_auto|
|Group|Graphic Editor|
|Descr.|The command performs an automatic step & repeat function for a specified set of panel parameters.|
|Response|nnn uuu - nnn: number of repeats, uuu - utilization percentage|


|----|----|
|Parameter| Value|
|step| Existing step in the job or in the library - step & repeat entity|
|num_mode| Multiple - multiple repeats are allowed<br>Single - single repeat is allowed|
|xmin, ymin| Legal coordinates - lower left corner of the panel|
|width, height| 0 <= size - panel size|
|panel_margin| 0 <= panel_margin - margin from the edge of the panel|
|step_margin| 0 <= step_margin - margin between the step profiles|
|gold_plate| Yes - consider gold plated connector no - no gold connectors|
|gold_side| Right, bottom, left, top - connector side on the repeated step|
|orientation| Any - horizontal and vertical horizontal vertical|
|evaluate| Yes - used only to evaluate the utilization (the calculated step & repeat is not applied)<br>No - the step & repeat is also applied|
|active_margins| Yes - the panel_margin is not considered. The top_active,,,etc are taken instead<br>No - the panel_margin is used|
|top_active<br>bottom_active<br>left_active<br>right_active|Active area margins (from the bottom_active panel edges)|
|step_xy_margin| Yes -<br>No -
|step_margin_x||
|step_margin_y||
|interlock_type| Default value = "none_interlock’<br>Solutions that allow interlocking by one dimension can be defined as "interlock_type =interlock_1dim".<br>Solutions that allow interlocking by two dimensions (sliding interlocking) can be defined as "interlock_type = interlock_2dim’.|
|allow_any_rotation| Non-orthogonal rotations can be written as "allow_any_rotation = yes". This enables testing of non-orthogonal rotations.|



<h2 id="sr_auto_class">sr_auto_class</h2>

|----|----|
|Command| sr_auto_class|
|Group|Graphic Editor|
|Descr.|The command performs a full automatic step & repeat operation. It is similar to the sr_auto but it takes all the panel constraints and possibilities from the panel classes file, and returns the best utilized panel.|
|Response|nnn uuu nnn: number of repeats<br>uuu - utilization percentage

|----|----|
|Parameter| Value|
|step| Existing step in the job or step & repeat entity in the library|
|num_mode| Multiple - multiple repeats are allowed<br>Single - single repeat is allowed|
|class| *filter (wildcard) - panel class filter|



<h2 id="sr_auto_popup">sr_auto_popup</h2>

|----|----|
|Command| sr_auto_popup|
|Group|Graphic Editor|
|Descr.|This command is used for invoking the step & repeat popup.|

|----|----|
|Parameter| Value|
|step| Existing step in the job or in the library - step & repeat entity|
|mode| panel_classes, parameters|
|num_mode| Multiple - multiple repeats are allowed<br>Single - single repeat is allowed|
|width, height| 0 <= size - panel size|
|panel_<br>margin|0 <= panel_margin - margin from the edge of the panel|
|step_margin| 0 <= step_margin - margin between the step profiles|
|orientation|Any - horizontal and vertical horizontal vertical|
|xmin, ymin| Lower left corner of panel|
|step_xy_<br>margin|Yes -<br>No -|
|step_margin_x<br>step_margin_y|Margins between the step profiles|
|class| wild card filter (acts as panelization class filter)|





<h2 id="sr_copy_step">sr_copy_step</h2>

|----|----|
無



<h2 id="sr_del_step">sr_del_step</h2>

|----|----|
無




<h2 id="sredit_popup">sredit_popup</h2>

|----|----|
|Command| sredit_popup|
|Group|Graphic Editor|
|Descr.|This command is used for invoking the step & repeat editor.|




<h2 id="sr_fill">sr_fill</h2>

|----|----|
|Command| sr_fill|
|Group|Graphic Editor|
|Descr.|The command is used for pattern filling between the step & repeat data to the edited step edges. The fill parameters are according to the ‘fill_params’ command.|


|----|----|
|Parameter| Value|
|polarity| Positive, negative|
|step_margin| Size (inches) - margin from the step edges (panel)|
|step_max_dist| 0 <= size (inches) - maximal distance from the step edges|
|sr_margin| Size (inches)- margin from the step & repeat profiles|
|nest_sr| Yes - use the lowest level of step & repeat<br>No - use the highest level of step & repeat|
|consider_feat| Yes - consider the layer features for filling<br>No - consider the step & repeat only|
|feat_margin| 0 <= size (inches)margin from the layer features|
|consider_drill| Yes - consider the drill layer holes<br>No - no drills|
|drill_margin| 0 <= size (inches)margin from the layer holes|
|dest| affected_layers - fill all the affected layers<br>layer_name - use the specified layer name|
|layer| Existing step layer name if (dest == layer_name)|
|attributes| Yes - add the current attr<br>No - no attributes|




<h2 id="sr_gold_side">sr_gold_side</h2>

|----|----|
|Command| sr_gold_side|
|Group|Graphic Editor|
|Descr.|This command is used for getting the gold connectors position in a PCB - for the step & repeat operation.|
|Response|Contains the position as an angle - 0’, ‘90’, ‘180’, ‘270’, ‘none’ (no gold connectors in the step’s outer layers).|


<h2 id="sr_make_step_grid">sr_make_step_grid</h2>
|----|----|
無

<h2 id="sr_move_step">sr_move_step</h2>

|----|----|

無


<h2 id="sr_pack_steps">sr_pack_steps</h2>
|----|----|

無
<h2 id="sr_popup">sr_popup</h2>

|----|----|
|Command| sr_popup|
|Group|Graphic Editor|
|Descr.|This command is used for invoking the step & repeat table.|



<h2 id="sr_reduce_nesting">sr_reduce_nesting</h2>

|----|----|
無


<h2 id="sr_replace_step">sr_replace_step</h2>

|----|----|

無

<h2 id="sr_sredit_sel_area_end">sr_sredit_sel_area_end</h2>

|----|----|
無




<h2 id="sr_sredit_sel_area_start">sr_sredit_sel_area_start</h2>
|----|----|
無

<h2 id="sr_sredit_sel_area_xy">sr_sredit_sel_area_xy</h2>
|----|----|
無

<h2 id="sr_sredit_sel_clear">sr_sredit_sel_clear</h2>
|----|----|
無

<h2 id="sr_sredit_sel_step_xy">sr_sredit_sel_step_xy</h2>
|----|----|
無

<h2 id="sr_tab_add">sr_tab_add</h2>

|----|----|
|Command| sr_tab_add|
|Group|Graphic Editor|
|Descr.|The command adds an entry to the step & repeat table.|

|----|----|
|Parameter| Value|
|line| 0 <= line (0 - last line) line (entry) number|
|step| Step that exists in the job or in the library - step to be repeated|
|x, y| Legal coordinates - anchor point|
|nx, ny| 1 <= nx, ny - number of repeats in each axis|
|dx, dy| Distance between the repeats|
|angle| 0, 90, 180, 270|
|mirror| Yes, No<br>around X axis



<h2 id="sr_tab_break">sr_tab_break</h2>

|----|----|
|Command|sr_tab_break|
|Group|Graphic Editor|
|Descr.|The command is used for breaking a single step & repeat line into several lines.|


|----|----|
|Parameter| Value|
|line| 1 <= line - line (entry) number|




<h2 id="sr_tab_change">sr_tab_change</h2>

|----|----|
|Command|sr_tab_change|
|Group|Graphic Editor|
|Descr.|The command changes an entry to the step & repeat table.|

|----|----|
|Parameter| Value|
|line| 1 <= line - line (entry) number|
|step| Step that exists in the job or in the library - step to be repeated|
|x, y| Legal coordinates - anchor point|
|nx, ny| 1 <= nx, ny - number of repeats in each axis
|dx, dy|0 <= dx, dy - distance between the repeats|
|angle| 0, 90, 180, 270|
|mirror| Yes - no<br>Around X axis|





<h2 id="sr_tab_del">sr_tab_del</h2>

|----|----|
|Command| sr_tab_del|
|Group|Graphic Editor|
|Descr.|The command deletes an entry from the step & repeat table.|

|----|----|
|Parameter| Value|
|line| 1 <= line - line (entry) number|




<h2 id="stretch_feat">stretch_feat</h2>

|----|----|
|Command| stretch_feat|
|Group|Graphic Editor|
|Descr.|Stretches a line feature in all the affected layers.|

|----|----|
|Parameter| Value|
|index| Feature index in the work layer. (Optional)<br>If index is not specified, Genesis looks for the feature according to coordinates.|
|x, y| Legal coordinates - feature coordinates|
|xs, ys| Legal coordinates - new line start point|
|xe, ye| Legal coordinates - new line end point|
|tol| 0 <= tol (mils) - snap tolerance|



<h2 id="tools_close">tools_close</h2>

|----|----|
|Command| tools_close|
|Group|Graphic Editor|
|Descr.|Used for closing the tools popup|

|----|----|
|Parameter| Value|
|force| If yes - tools popup is closed even if it was changed during the session.|


<h2 id="tools_list_add">tools_list_add</h2>

|----|----|
|Command| tools_list_add|
|Group|Graphic Editor|
|Descr.|The command is used for adding a tool to a table that is used by the tools_list_set command.|

|----|----|
|Parameter| Value|
|num| 1 <= num - tool number|
|size| 0 <= size - drill size|



<h2 id="tools_list_reset">tools_list_reset</h2>

|----|----|
|Command| tools_list_reset|
|Group|Graphic Editor|
|Descr.|The command resets the tools list that is used by the - ‘tools_list_set’ command.|



<h2 id="tools_list_set">tools_list_set</h2>

|----|----|
|Command| tools_list_set|
|Group|Graphic Editor|
|Descr.|The command sets the tool sizes.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|



<h2 id="tools_merge_ex">tools_merge_ex</h2>

|----|----|
|Command| tools_merge_ex|
|Group|Drill Tool Manager|
|Description|Defines how tool merges are processed in the Drill Tool Manager|

|----|----|
|Parameter| Value|
|mode|merge - merge tools and update tool numbers<br>merge_keep_tool - merge tools and keep tool numbers<br>merge_and_sort - merge tools and sort tool entries|



<h2 id="tools_set">tools_set</h2>

|----|----|
|Command| tools_set|
|Group|Graphic Editor|
|Description|The command sets the tool parameters (including sizes) of a drill/rout layer. The tools table is defined by the commands:<br>•tools_tab_reset <br>•tools_tab_add|


<h2 id="tools_show">tools_show</h2>

|----|----|
|Command| tools_show|
|Group|Graphic Editor|
|Descr.|The command is used for showing the tools popup.|

|----|----|
|Parameter| Value|
|layer| Existing layer name|



<h2 id="truncate_layer">truncate_layer</h2>

|----|----|
|Command| truncate_layer|
|Group|Graphic Editor|
|Descr.|The command is used for truncating a layer’s contents. The undo information is cleared.Thus, after running this command the **undo** operation cannot be performed.|


|----|----|
|Parameter| Value|
|layer| Entity name|



<h2 id="undo">undo</h2>


|----|----|
|Command| undo|
|Group|Graphic Editor|
|Descr.|Undoes the last editor change.|

<h2 id="units">units</h2>

|----|----|
|Command| units|
|Group|Graphic Editor|
|Descr.|Sets the working units.|

|----|----|
|Parameter| Value|
|type| Inch, mm|

<h2 id="update_dependent_step">update_dependent_step</h2>

|----|----|
|Command| update_dependent_step|
|Group|Engineering Toolkit|
|Descr.|Supports update of dependent steps|

|----|----|
|Parameter| Value|
|job| valid job name|
|step| valid step name|




<h2 id="user_delete">user_delete</h2>

|----|----|
|Command| user_delete|
|Group|Login|
|Descr.|Used for deleting user entries|

|----|----|
|Parameter| Value|
|name| Login name of user|


<h2 id="user_edit">user_edit</h2>

|----|----|
|Command| user_edit|
|Group|Login|
|Descr.|Used for changing/adding user entries|
|Response|None|

|----|----|
|Parameter| Value|
|name| Login name of user|
|real_name| Real name of user|
|priv| 1 - 100|
|autologout| Minutes before autologout|
|group| Group name|


<h2 id="wheel_current">wheel_current</h2>

|----|----|
|Command| wheel_current|
|Group|Wheel Editor|
|Descr.|The command is used for setting the current wheel name, which is used by all the other line mode commands.|

|----|----|
|Parameter| Value|
|job| Existing opened job name|
|wheel| Existing opened wheel name|


<h2 id="wheel_page_close">wheel_page_close</h2>

|----|----|
|Command |wheel_page_close|
|Group|Wheel Editor|
|Descr.|The command closes a wheel page.|



<h2 id="work_layer">work_layer</h2>

|----|----|
|Command| work_layer|
|Group|Graphic Editor|
|Descr.|Assigns the work layer.|

|----|----|
|Parameter| Value|
|name| Entity name|



<h2 id="zoom_area">zoom_area</h2>

|----|----|
|Command| zoom_area|
|Group|Graphic Editor|
|Descr.|Zoom the display to a specified area.|

|----|----|
|Parameter| Value|
|x1, y1| Legal coordinates - first corner|
|x2, y2| Legal coordinates - second corner|


<h2 id="zoom_back">zoom_back</h2>

|----|----|
|Command| zoom_back|
|Group|Graphic Editor|
|Descr.|Go back to the previous zoom state.|





<h2 id="zoom_home">zoom_home</h2>

|----|----|
|Command| zoom_home|
|Group|Graphic Editor|
|Descr.|Zoom the display to the step limits (+ margin).|



<h2 id="zoom_in">zoom_in</h2>

|----|----|
|Command| zoom_in|
|Group|Graphic Editor|
|Descr.|Zoom the display in.|

<h2 id="zoom_out">zoom_out</h2>

|----|----|
|Command| zoom_out|
|Group|Graphic Editor|
|Descr.|Zoom the display out.|


<h2 id="zoom_pv_close">zoom_pv_close</h2>

|----|----|
|Command| zoom_pv_close|
|Group|Graphic Editor|
|Descr.|Closes a popview (s).|

|----|----|
|Parameter| Value|
|all| Yes - close all popviews<br>No - close only one popview|
|popview| bigger than 0 - popview number as it is returned from zoom_pv_open|



<h2 id="zoom_pv_move">zoom_pv_move</h2>

|----|----|
|Command| zoom_pv_move|
|Group|Graphic Editor|
|Descr.|Move a pop-view window.|

|----|----|
|Parameter| Value|
|popview| Bigger than 0 - popview number as it is returned from zoom_pv_open|
|x1, y1,<br>x2, y2|New window size and position|



<h2 id="zoom_pv_open">zoom_pv_open</h2>

|----|----|
|Command| zoom_pv_open|
|Group|Graphic Editor|
|Descr.|Open a pop-view window.|
|Response|Popview number (can be used by the other popview commands)|

|----|----|
|Parameter| Value|
|x1, y1,<br>x2, y2|Legal coordinates - display coordinates|
|x_win,<br>y_win-|2000 < coord < 2000 - pop-view coordinates (screen coords)|
|w_win,<br>h_win1|< size < 2000 - window size (pixels)|



