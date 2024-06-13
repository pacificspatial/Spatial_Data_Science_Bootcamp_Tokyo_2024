# 資料</br>
## - <a href="https://bootcamp24.s3.ap-northeast-1.amazonaws.com/【投影資料】spatial_indexes_2024.pdf">【投影資料】spatial_indexes_2024.pdf</a>：イベント時の投影資料</br>
## - <a href="https://bootcamp24.s3.ap-northeast-1.amazonaws.com/【補足資料】一からWorkflowsを作成する手順.pdf">【補足資料】一からWorkflowsを作成する手順.pdf</a>：一からWorkflowsを作ってみたい方用の手順資料</br>

</br>
# CARTOログイン</br>
## - <a href="https://carto.com">CARTOのログイン</a></br>

</br>
# ワークフローファイル</br>
## - <a href="https://bootcamp24.s3.ap-northeast-1.amazonaws.com/bootcamp_tokyo_2024_Workflows.sql">Workflowのテンプレート</a></br>

</br>
# 使用データ</br>
## - <a href="https://bootcamp24.s3.ap-northeast-1.amazonaws.com/mdp_2021_reprojecter.parquet">⽇本全国</a></br>
## - <a href="https://bootcamp24.s3.ap-northeast-1.amazonaws.com/mdp_2021_reprojector_kanto.gpkg">関東のみ</a></br>
※出典：「全国の⼈流オープンデータ」（国⼟交通省）
（<a href="https://www.geospatial.jp/ckan/dataset/mlit-1km-fromto">https://www.geospatial.jp/ckan/dataset/mlit-1km-fromto</a>）を加⼯して作成
       
</br>
# select文：
```
(_1_0_0+_2_0_0+_3_0_0+_4_0_0+_5_0_0+_6_0_0+_7_0_0+_8_0_0+_9_0_0+_10_0_0+_11_0_0+_12_0_0)/12 as weekdays_daytime_ave,(_1_0_1+_2_0_1+_3_0_1+_4_0_1+_5_0_1+_6_0_1+_7_0_1+_8_0_1+_9_0_1+_10_0_1+_11_0_1+_12_0_1)/12 as weeddays_nigt_ave,(_1_1_0+_2_1_0+_3_1_0+_4_1_0+_5_1_0+_6_1_0+_7_1_0+_8_1_0+_9_1_0+_10_1_0+_11_1_0+_12_1_0)/12 as weekend_daytime_ave,(_1_1_1+_2_1_1+_3_1_1+_4_1_1+_5_1_1+_6_1_1+_7_1_1+_8_1_1+_9_1_1+_10_1_1+_11_1_1+_12_1_1)/12 as weekend_night_ave,(_1_2_0+_2_2_0+_3_2_0+_4_2_0+_5_2_0+_6_2_0+_7_2_0+_8_2_0+_9_2_0+_10_2_0+_11_2_0+_12_2_0)/12 as daytime_ave, (_1_2_1+_2_2_1+_3_2_1+_4_2_1+_5_2_1+_6_2_1+_7_2_1+_8_2_1+_9_2_1+_10_2_1+_11_2_1+_12_2_1)/12 as night_ave,(_3_2_0+_4_2_0+_5_2_0)/3 as spring_daytime_ave, (_6_2_0+_7_2_0+_8_2_0)/3 as summer_daytime_ave, (_9_2_1+_10_2_1+_11_2_1)/3 as autumn_daytime_ave,(_1_2_0+_2_2_0+_12_2_0)/3 as winter_daytime_ave
```
</br>
# 完成した地図</br>
- <a href="https://thunbergii.app.carto.com/map/3a6afe8a-d1c9-448e-b881-1f24f9a8dd8e?lat=35.561346&lng=139.772310&zoom=9">完成した地図</a></br>
</br>
※一部のデータが表示できていなかったため、リンク先を差し替えました。（2024/6/7 PM16:50）
