# transfer_matrix_mode_soluter
求解1D模式
更新v1.1:
由于衬底折射率为1时远小于材料，导致γ在空气中很小，虽然Az收敛至很小，但随着距离很快光场发散。继续减小Az值意义不大，对材料内光场影响很小，因此调整为在求电场时在衬底中不包含Az项
加入了限制因子的计算
