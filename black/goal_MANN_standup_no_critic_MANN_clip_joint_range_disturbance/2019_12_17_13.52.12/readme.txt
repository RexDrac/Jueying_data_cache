train-step-num: 1
prioritized-exp-replay: True
critic-layer-size: [256, 256]
filter-torque: False
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-l2-reg: 0.0003
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
interpolation: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
Physics-frequency: 1000
critic-l2-reg: 0.0003
critic-lr: 0.0003
replay-buffer-size: 1000000
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.986
action-dim: 12
state-dim: 25
imitation-weight: 0.4
epoch-step-num: 5000000
replay-start-size: 10000
max-path-step: 5000
max-test-time: 10
LLC-frequency: 500
joint-interpolation: True
batch-size: 128
loss-output-diff-coeff: 0
total-step-num: 2500000000
dsr-gait-freq: 1.667
actor-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
max-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
goal-weight: 0.4
replay-ratio: 1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
expert-num: 8
record-start-size: 10000.0
test-num: 4
n-step: 1
loss-output-bound-coeff: 0.0
dsr-gait-period: 0.6
task-weight: 0.2
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
gating-layer-size: [128, 128]
HLC-frequency: 25
epoch-num: 500
max-episode-num: 5000000
max-train-time: 10
max-path-num: 20
reward-scale: 0.1
loss-output-smooth-coeff: 2.0
tau: 0.001
