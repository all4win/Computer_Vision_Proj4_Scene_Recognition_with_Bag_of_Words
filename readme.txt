Project 4 by Tiancheng Gong(tgong7)

Settings:

Part 1:
nearest_neighbor_classify.m		K of KNN      					1, 5, 10, 15

Part 2:
build_vocabulary.m			number of features selected from each image	30
					step size of vl_dsift				10
get_bags_of_sifts.m			step size of vl_dsift				10
					K of KNN(feature match)				10					
nearest_neighbor_classify.m		K of KNN      					5

Part 3:
svm_classify.m				LAMBDA						0.0001
					max number of iterations			10 / LAMBDA;