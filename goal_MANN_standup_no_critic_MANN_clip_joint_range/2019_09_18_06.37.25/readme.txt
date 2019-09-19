action-dim: 12
render-eval: False
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
max-path-num: 20
record-start-size: 10000.0
imitation-weight: 0.5
replay-buffer-size: 1000000
LLC-frequency: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
max-episode-num: 5000000
loss-output-smooth-coeff: 1.0
replay-ratio: 1
batch-size: 128
gamma: 0.986
actor-weight-decay: 1e-06
reward-scale: 0.1
actor-layer-size: [256, 256]
replay-start-size: 10000
max-train-time: 10
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
n-step: 1
rollout-step-num: 1
interpolation: False
actor-lr: 0.0003
gating-layer-size: [128, 128]
epoch-step-num: 5000000
env-id: HumanoidBalanceFilter-v0
expert-num: 8
epoch-num: 500
tau: 0.001
max-test-time: 10
gating-activation-fn: ['tanh', 'tanh', 'None']
dsr-gait-period: 0.6
total-step-num: 2500000000
Physics-frequency: 1000
HLC-frequency: 25
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
bullet-default-PD: False
squash-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
task-weight: 0.5
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-entropy-coeff: 0.0
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
filter-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
critic-lr: 0.0003
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
filter-torque: False
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
prioritized-exp-replay: True
test-num: 4
state-dim: 25
